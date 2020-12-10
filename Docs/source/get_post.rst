**************************************************
Get Post
**************************************************
It fetches data of post passed in ``post_link``.

Here is the code:-

.. py:function:: linkedin.get_post(post_link="post_link")

   
   :param str post_link: Link of post whose data need to be fetched
   :return: {'Post Text': 'Post Text', 'Bio': 'Bio', 'Time': 'Time', 'Likes': 'Likes', 'Comments': 'Comments', 'Profile_Link': 'Profile_Link', 'UserName': 'UserName'}
   :rtype: dict