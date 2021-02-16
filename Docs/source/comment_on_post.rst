**************************************************
Comment On Post
**************************************************
It comments on the post passed in ``post_link`` with comment in ``comment``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: linkedin.comment_on_post(post_link="https://www.linkedin.com/posts/er-chirag-grover-290918101_help-androiddevelopment-flutterappdevelopment-activity-6766960247794937856-2jh3",comment="Please share your resume here abc@gmail.com")

   
   :param str post_link: post link where need to comment
   :param str comment: Text need to comment on post
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
