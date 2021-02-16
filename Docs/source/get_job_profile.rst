**************************************************
Get Job Profile
**************************************************
It opens the job link passed in ``job_link`` and fetches info about job.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.get_job_profile(job_link="https://www.linkedin.com/jobs/search?keywords=python&origin=BLENDED_SEARCH_RESULT_CARD_NAVIGATION&currentJobId=2369119694&lipi=urn%3Ali%3Apage%3Ad_flagship3_search_srp_all%3B0Rk7LgXJQnKGvr4mUZFYVg%3D%3D")

   
   :param str job_link: Link of the job posted
   :return: {"body": {'Location': 'Location', 'Employment Type': 'Employment Type', 'Company Name': 'Company Name', 'Industry': 'Industry', 'Experience': 'Experience', 'Roles': 'Roles', 'Job Functions': 'Job Functions', 'Applicants': 'Applicants', 'Title': 'Title', 'Published': 'Published', 'Seniority Level': 'Seniority Level'}, "success_score": "100", "errors": []}
   :rtype: dict
