**************************************************
Open Connections
**************************************************
It opens connections of the user passed in ``profile_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.open_connections(profile_link="profile_link")

   
   :param str profile_link: Profile link whose connections need to be opened
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict