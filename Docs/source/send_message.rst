**************************************************
Send Message
**************************************************
It sends message to user passed in ``profile_link`` with ``message`` as message.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.send_message(message="message",profile_link="profile_link")

   
   :param str message: message which need to be send
   :param str profile_link: profile link of user whom message need to be sent
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict