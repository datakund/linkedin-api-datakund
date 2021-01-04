**************************************************
Search Groups
**************************************************
It searches the keyword passed in ``keyword`` and opens group results.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.search_groups(keyword="keyword")

   
   :param str keyword: Search keyword like python,machine learning
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict