**************************************************
Get Job Profile
**************************************************
It opens the job link passed in ``job_link`` and fetches info about job.

Here is the code:-

.. py:function:: linkedin.get_job_profile(job_link="job_link")

   
   :param str job_link: Link of the job posted
   :return: {'Title': 'Title', 'Company Name': 'Company Name', 'Location': 'Location', 'Published': 'Published', 'Applicants': 'Applicants', 'Experience': 'Experience', 'Roles': 'Roles', 'Seniority Level': 'Seniority Level', 'Industry': 'Industry', 'Employment Type': 'Employment Type', 'Job Functions': 'Job Functions'}
   :rtype: dict