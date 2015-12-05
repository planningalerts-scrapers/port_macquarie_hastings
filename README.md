# Port Macquarie Hastings Council Scraper

Port Macquarie Hastings Council involves the followings
* Server - Apache (Red Hat) - Super slow web site
* Cookie tracking - Yes
* Pagnation - No - However, query is based on date submit via POST
* Javascript - No
* Clearly defined data within a row - No and it is so bad that I need to make an extra call to the actual DA to read information
* Very limited description about a DA

Setup MORPH_PERIOD for data recovery, available options are
* thisweek (default)
* thismonth
* lastmonth

Enjoy
