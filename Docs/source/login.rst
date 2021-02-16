**************************************************
Login
**************************************************
It will login to linkedin via your credentials.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.login(username="datakund@gmail.com",password="password@123")

   
   :param str username: Linkedin username
   :param str password: Linkedin password
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
