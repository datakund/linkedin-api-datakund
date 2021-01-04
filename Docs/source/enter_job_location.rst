**************************************************
Enter Job Location
**************************************************
It fills location passed in ``location`` on search results page.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.enter_job_location(location="location")

   
   :param str location: pass location like delhi,goa
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict