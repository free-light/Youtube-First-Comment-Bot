# Youtube-First-Comment-Bot
A bot for automatically post comment when a youtube channel upload a new video.
This bot checks a specified channel every specified intervel and if a new video found this bot will post a comment that you wants to post.

Requirments
python 2.7
google api client modules
google api console account
Youtube account

Usage
Create an account and a api and a outh screen in google console
Replace the file "client_secrets.json" with the downloaded Credentials json file from google console
Edit these variables in bot.py
  cid="UUX6OQ3DkcsbYNE6v8uQQuVA" puth uploads id of the required channel here. (
  lastvid="Z9WQy9uEY8M"  put last video id here 
  intervel=5 put the time waiting intervel here
  comment="Put your text here"  edit this variable amnd put the required comment here.


Helps
How to find upload it? see this video https://www.youtube.com/watch?v=RjUlmco7v2M .
To find last video go the the required channel and check the url of the latest upload an url may look like this https://www.youtube.com/watch?v=RjUlmco7v2M take the last string that is "RjUlmco7v2M" this is video id.
To set up a good time intervel you must consider several things eg youtube api quata limit system resources etc... if you planed to run this bot 24x7 then put the inyer vell as 20 to 25 seconds, if you are running this bot only for one or two hour you can put this intervel as 1 or 2 seconds. this is to prevent youtube api limit.
