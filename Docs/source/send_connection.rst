**************************************************
Send Connection
**************************************************
It sends conection request to the user passed in ``profile_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.send_connection(profile_link="https://www.linkedin.com/in/abhishek-chaudhary-/")

   
   :param str profile_link: Profile link of user to whom connection need to be sent
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
