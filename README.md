# Bitcoin trade data scraper 

This is a chrome extension that scrapes data that is not normally available on bitcoin sites' APIs.  In order to use this bot, you should have knowledge of php and mySQL or some other form of backend/database. And javascript.

# How to use - 2 ways
##Use it directly
1. Clone the repo to your computer
2. Go to Extensions in Chrome
3. Make sure `Developer Mode` is checked
4. Click on `load unpacked extensions` then click `enable`
5. Open Chrome developer tools and watch the magic happen.

##Customize it and how to save to your database:
The code is currently set up to scrape bitstamp.com's data but if you want to customize it to your bitcoin site of choice, just do the following: 

1. Go to content.js  
2. Change line 16 to the bitcoin site of your choice
3. Change the code from lines 30 ~ 33 so that it contains the variables/values pertaining to the site of your choice.  You would know this by inspecting the elements of the site.
4. In the AJAX part on line 38 where it says `url`, change the URL to the one you're using to connect to your database.
