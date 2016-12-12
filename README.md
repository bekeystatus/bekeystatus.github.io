# Changing the status bar
Edit __config.yml_.
At the top, change the _status_ variable to one of the following:
* okay<br />
The status will say "No known operational issues" and be green.
* warn<br />
The status will say that some services are not functioning correctly and to follow the blog for updates.
* error<br />
The status will say that there is a critical problem with the service and to follow the blog below for details and updates.

Trigger a rebuild of the pages by committing and pushing the _master_ branch.
