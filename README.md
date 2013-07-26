Teen Denton Police
==================

Fork to only log inmates that are teenagers (under 20 years of age)

Available at: https://twitter.com/TeenArrests

Scrapes mug shot and inmate information from the City Jail Custody
Report page for Denton, TX and posts some of the information to Twitter
via TwitPic.

The City Jail Custody Report page that we are scraping is available here:
http://dpdjailview.cityofdenton.com/

Configuration is first required in order to post to TwitPic or Twitter. Without configuration the program will still scrape mug shots and log the images and inmate information to disk.

How to Run
==========

1. Enter your Twitpic send email address (usually in the format <username>.<4_digit_code>@twitpic.com) in `scanner.py`

2. Enter a gmail username and password to send the email to Twitpic, in the `sender.py` file

3. Execute the command `python scanner.py` to start the process. It will automatically run every minute.

I would recommend running the above command after running `screen` if you are on a server.