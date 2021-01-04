**************************************************
Search Companies
**************************************************
It searches the keyword passed in ``keyword`` and opens companies results.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.search_companies(keyword="keyword")

   
   :param str keyword: Search keyword like microsoft,google
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict