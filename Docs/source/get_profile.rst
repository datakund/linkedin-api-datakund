**************************************************
Get Profile
**************************************************
It fetches the profile of the user passed in ``profile_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.get_profile(profile_link="https://www.linkedin.com/in/abhishek-chaudhary-/")

   
   :param str profile_link: Profile link of user whose data need to be fetched
   :return: {"body": {'Location': 'Location', 'Info': 'Info', 'Education': 'Education', 'About': 'About', 'Experience': 'Experience', 'Education_Info': 'Education_Info', 'Recommendations': 'Recommendations', 'Mutual_Connections': 'Mutual_Connections', 'Name': 'Name', 'Interests': 'Interests', 'Current Company': 'Current Company'}, "success_score": "100", "errors": []}
   :rtype: dict
