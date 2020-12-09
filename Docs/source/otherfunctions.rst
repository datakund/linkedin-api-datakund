Other Functions
**************************************************
You can use basic functions which selenium provides with this library like opening a url, get pagesource, get current url etc. These are the functions:-

Open
========

It will open the url provided in the argument.

.. code-block:: python

	linkedin.open("https://www.linkedin.com/")
	
Get Page Title
=================

It returns the title of page opened.

.. code-block:: python

	res=linkedin.get_page_title()
	#res={"pagetitle":"Linkedin"}

Get Page Source
===================

It returns the pagesource of page opened.

.. code-block:: python

	res=linkedin.get_page_source()
	#res={"pagesource":"pagesource"}

Get Current Url
===================

It returns the pagesource of page opened.

.. code-block:: python

	res=linkedin.get_current_url()
	#res={"url":"https://www.linkedin.com/"}

Reload
===================

It reloads the page opened.

.. code-block:: python

	res=linkedin.reload()

Keypress
===================

It perform the keypress passed.

.. code-block:: python

	res=linkedin.keypress("pagedown")

End
===================

It ends the linkedin session and close the automated chromedriver.

.. note:: You will need to create linkedin object again after ``end()``.

.. code-block:: python

	linkedin.end()
	
Quit
===================

It quits the datakund application runing in background.

.. note:: You will need to import datakund library again to start datakund application.

.. code-block:: python

	linkedin.quit()