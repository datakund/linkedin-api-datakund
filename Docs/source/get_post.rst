**************************************************
Get Post
**************************************************
It fetches data of post passed in ``post_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.get_post(post_link="https://www.linkedin.com/feed/update/urn:li:activity:6764456234197295104?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A6764456234197295104%29")

   
   :param str post_link: Link of post whose data need to be fetched
   :return: {"body": {'Time': 'Time', 'Post Text': 'Post Text', 'Profile_Link': 'Profile_Link', 'Likes': 'Likes', 'UserName': 'UserName', 'Bio': 'Bio', 'Comments': 'Comments'}, "success_score": "100", "errors": []}
   :rtype: dict
