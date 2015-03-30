# web-crawler
A Python based web crawler to crawl and index tons of web pages

## Summary
This is a Python script to download, crawl and index the web in sequential manner. It uses a breath-first search technique to crawl all the webpages on a given domain and even outside the domain. 

## Compatability
This program is written in Python 3.4 and can run on any version of Ptyhon (3.x). It is a download-and-run program with couple of changes according to requirements.

## Status
This is a small script which is ready-to-run, but still under development. Many more features will be added to it shortly.

## Usage
As mentioned, it is a ready-to-run script. Just mention the web url that you want to start crawling from in the `reference_seed_page` variable.

`reference_seed_page = "http://www.zseries.in"`


## Disclaimer
This program lets you download  and crawl tons of web pages. Please do not download and crawl any pages of a domain without reading about the robot.txt file of that domain. It is inappropriate to violate the robot.txt file. This may even lead to the domain completely blocking your crawler and thus blacklisting it. It is also not appropriate to crawl pages at high rate as it may put a lot of pressure on the server.
