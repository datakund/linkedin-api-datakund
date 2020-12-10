**************************************************
Get Profile
**************************************************
It fetches the profile of the user passed in ``profile_link``.

Here is the code:-

.. py:function:: linkedin.get_profile(profile_link="profile_link")

   
   :param str profile_link: Profile link of user whose data need to be fetched
   :return: {'Name': 'Name', 'Info': 'Info', 'Location': 'Location', 'Current Company': 'Current Company', 'Education': 'Education', 'About': 'About', 'Mutual_Connections': 'Mutual_Connections', 'Experience': 'Experience', 'Education_Info': 'Education_Info', 'Skills': 'Skills', 'Recommendations': 'Recommendations', 'Interests': 'Interests'}
   :rtype: dict