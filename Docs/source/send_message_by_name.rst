**************************************************
Send Message By Name
**************************************************
It searches the keyword passed in ``keyword`` and clicks on first search result and send message passed in ``message``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.send_message_by_name(message="Hi",keyword="DataKund")

   
   :param str message: Text need to comment on post
   :param str keyword: Name of the user who need to be searched
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
