**************************************************
Get Company Profile
**************************************************
It fetches the profile of the company passed in ``company_link``.

Here is the code:-

.. py:function:: linkedin.get_company_profile(company_link="company_link")

   
   :param str company_link: Company link  whose data need to be fetched
   :return: {'Company Name': 'Company Name', 'Followers': 'Followers', 'Info': 'Info', 'Overview': 'Overview', 'Website': 'Website', 'Industry': 'Industry', 'Company Size': 'Company Size', 'Location': 'Location', 'Type': 'Type', 'Founded': 'Founded', 'Specialities': 'Specialities'}
   :rtype: dict