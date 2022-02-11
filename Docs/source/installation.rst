Installation/Usage:
*******************
You can find this package on Pypi (see `here <https://pypi.org/project/bot-studio/>`_).

Command to install :- ``pip install bot-studio``

Import bot-studio
**************************************************
.. code-block:: python

	from bot_studio import *

Creating Object
**************************************************
.. code-block:: python
	
	linkedin=bot_studio.linkedin()
	or
	linkedin=bot_studio.linkedin(headless=True,....)
	
It will return the object which you can further use to call linkedin functions and opens a automated browser

Browser Options
################

.. list-table:: 
   :widths: 25 25 50
   :header-rows: 1

   * - Option
     - Default Value
     - Description
   * - headless
     - False
     - Can set it to True if wants headless
   * - proxy
     - No proxy
     - Pass proxy value e.g 98.0.2.5:4000
   * - profile_path
     - creates temporary profile
     - Pass profile path e.g C:\\Users\\username\\AppData\\Local\\Google\\Chrome\\User Data\\
   * - user_agent
     - No user agent
     - Pass user agent e.g python 2.7", "platform":"Windows
   * - download_folder
     - Downloads in default folder
     - If want to set download directory to custom e.g E:files\\
