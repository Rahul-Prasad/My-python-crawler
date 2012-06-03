My-python-crawler
=================

A simple crawler where I took takes care of ValueError, HTTPError, URLError, InvalidURL, HTMLParseError with try-catch. I also maintained and temporary cache of 5000 good and bad urls to speed up the process. the System stores output in a file OUTPUT.txt. Only distinct URLs and those URLs that will open in browser without errors are stored. A URL is assumed to be giving error if it gives a response code higher than equal to 400.