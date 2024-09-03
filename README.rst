==============
Web Scrapping
==============


Scrapy is a BSD-licensed fast high-level web crawling and web scraping framework, used to
crawl websites and extract structured data from their pages. It can be used for
a wide range of purposes, from data mining to monitoring and automated testing.

Scrapy is maintained by Zyte_ (formerly Scrapinghub) and `many other
contributors`_.

Check the Scrapy homepage at https://scrapy.org for more information,
including a list of features.

=======
Detail
=======
A scrapy project to extract the text and metadata of articles from news websites.

This should provide much of the structure and parsing code needed to fetch from arbitrary news websites. It may work out-of-the-box on some or more of the sites with specific spiders already written (see below) but be aware that web scrapers are by their nature somewhat brittle: they depend on the underlying format and structure of each site's pages, and when these are changed they tend to break. Although RISJbot has a fallback scraper that does a reasonable job with arbitrary news pages, it's not a substitute for a hand-tailored spider.

Having some degree of experience with Python would be very helpful. If sites update their templates or you want to add a new site to the collection then some coding will be necessary. I've tried to ensure that the existing code is well commented. The Scrapy docs are themselves quite good if you find yourself needing to understand what is going on behind the scenes.

You should be aware that this was written to support the author's academic research into online news. It is still actively (if slowly) developed for that purpose, but it is not production-level code and comes with even fewer guarantees than most Free software.
