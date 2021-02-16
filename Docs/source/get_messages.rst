**************************************************
Get Messages
**************************************************
It fetch messages of user passed in ``profile_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.get_messages(profile_link="https://www.linkedin.com/in/abhishek-chaudhary-/")

   
   :param str profile_link: Profile link whose messages need to be fetched
   :return: {"body": {'Messegetext': 'Messegetext'}, "success_score": "100", "errors": []}
   :rtype: dict
