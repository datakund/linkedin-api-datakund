**************************************************
Search People
**************************************************
It searches the keyword passed in ``keyword`` and opens people.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.search_people(keyword="Hr manager")

   
   :param str keyword: Keyword need to be searched like hr,python
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
