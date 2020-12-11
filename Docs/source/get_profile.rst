**************************************************
Get Profile
**************************************************
It fetches the profile of the user passed in ``profile_link``.

Here is the code:-

.. py:function:: linkedin.get_profile(profile_link="profile_link")

   
   :param str profile_link: Profile link of user whose data need to be fetched
   :return: {'Education_Info': 'Education_Info', 'About': 'About', 'Experience': 'Experience', 'Name': 'Name', 'Recommendations': 'Recommendations', 'Current Company': 'Current Company', 'Education': 'Education', 'Info': 'Info', 'Interests': 'Interests', 'Location': 'Location', 'Mutual_Connections': 'Mutual_Connections'}
   :rtype: dict