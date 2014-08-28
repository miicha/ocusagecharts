ocUsageCharts ( STILL WORK IN PROGRESS )
========================================
ocUsageCharts is created due to the fact that the original usage_charts is no longer updated to work properly with owncloud 7.
This application is from the base up designed for owncloud 7.
ocUsageCharts uses C3.js for rendering the charts on the dashboard.

Features
========
- ocUsageCharts stores the disk space used by each user of ownCloud.
- Graphs available:
	- User mode:
		- A pie chart showing space used / free space
		- A graph with data used over the course of the last month
		- A Bar chart with average data used in the last months
	- Admin mode
		- A pie chart showing space used by all users
		- A graph with data used over the course of the last month for all users
		- A Bar chart with average data used in the last months for all users

Future ideas
============
Graphs:
    - A bar graph, with usages per month over the course of last year
    - Files downloaded
    - Activity tracking
    - Option to use alternative for C3.js

INSTALL
=======
TODO

Product reference
=================
- C3.js: http://c3js.org/ - https://github.com/masayuki0812/c3
- usage_charts: http://apps.owncloud.com/content/show.php/Usage+Charts?content=164956 - https://github.com/alanv72/usage_charts ( a fork from StorageCharts/ocStorage )