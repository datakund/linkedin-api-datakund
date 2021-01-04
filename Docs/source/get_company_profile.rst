**************************************************
Get Company Profile
**************************************************
It fetches the profile of the company passed in ``company_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.get_company_profile(company_link="company_link")

   
   :param str company_link: Company link whose data need to be fetched
   :return: {"body": {'Location': 'Location', 'Company Name': 'Company Name', 'Industry': 'Industry', 'Info': 'Info', 'Followers': 'Followers', 'Overview': 'Overview', 'Type': 'Type', 'Founded': 'Founded', 'Website': 'Website', 'Company Size': 'Company Size', 'Specialities': 'Specialities'}, "success_score": "100", "errors": []}
   :rtype: dict