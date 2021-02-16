**************************************************
Login Cookie
**************************************************
It will login to linkedin via your cookies.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.login_cookie(cookies=[{"domain": ".linkedin.com","expirationDate": 1676524503,"hostOnly": false,"httpOnly": false,"name": "_ga",},...])

   
   :param str cookies: list of cookies of linkedin
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
