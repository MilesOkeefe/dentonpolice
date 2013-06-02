Teen Denton Police
=============
Fork to only log inmates that are teenagers (under 20 years of age)

Available at: https://twitter.com/TeenArrests

Scrapes mug shot and inmate information from the City Jail Custody
Report page for Denton, TX and posts some of the information to Twitter
via TwitPic.

The City Jail Custody Report page that we are scraping is available here:
http://dpdjailview.cityofdenton.com/

Configuration is first required in order to post to TwitPic or Twitter. Without configuration the program will still scrape mug shots and log the images and inmate information to disk.

If run as __main__, will loop and continuously check the report page.
To run only once, execute this module's main() function.