OSCAR-F
=======

Python OSINT Platform

**OSCARf was coded/designed in Linux and Mac. Don't complain if you are running Windows and you cannot get it working**
Windows support is something that I am going to address at a later date.

OSCAR-F is designed to aid in the process of information gathering. It was formed with the idea of not having to open
so many tabs in a browser.

There are a few bugs in OSCAR-F, however, we are slowly working on crushing them and working on features.

## Installing

OSCAR uses a few libraries. These include:

- Twitter
- tweepy
- feedparser
- shodan
- readline
- pillow

These can be installed via pip: `pip install -r requirements.txt`

**Please note that you will need to setup ONE twitter app for you/your business.**

~**You will probably need to use sudo to run the setup script. This is becasue it creates files and directories.**~

The the readline feature is completely optional.

Please be sure to run the `DEPENDENCY_CHECK` script first! Additionally, as noted above,  dependencies can be installed via `pip install -r requirements.txt`

After running the dependency check, run the setup.py script. This will allow you to setup all necessary auth files/data.
**PLEASE NOTE THAT THE SETUP SCRIPT WILL NOT INSTALL MISSING LIBRARIES! Please use pip.**

## To scrape pastebin

To scrape pastebin, add regex strings to pSearch.dat located in the root directory. After this, proceed to use oscar.

## To edit rss filter options

Edit the keywords in /rss/filter.dat

## To add/remove rss feeds

Edit rss links in /rss/feeds.dat

## To scrape web source code

Edit regex info in webscrape.dat in the root. The path will change soon. 
