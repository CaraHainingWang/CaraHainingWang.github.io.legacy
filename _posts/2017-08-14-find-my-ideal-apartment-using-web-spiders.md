---
layout: post
title: "Find My Ideal Apartment Using Web Spiders"
date: 2017-08-04
---

<p>Apartment hunting is a painful experience. And if you are like me who struggled
to move with my newborn baby to the San Francisco Bay Area, you are more picky
locations, amenities and prices, which implies you have to spend even more time to browse
through websites to make sure everything is good.</p>

<p>To make things worse, I may not be able to drive and have to take advantage of
the company's shuttle since my husband is going to do some long distance commute
with our car. I need to make sure the apartment is super close to some shuttle
stop (say ten minutes by foot). Checking each potential apartment to all nearby
shuttle stations is another tedious job to do. In order to not repeating the whole
process, I will probably need to have a spreadsheet writing down addresses and
whether there is any station that is close to the apartment. To make matters worse,
apartments can quickly become unavailable and great choices can suddenly come
up as well, which means I should not only browse, but literally watches the changes.</p>


<p> After spending a few hours looking on the Internet. I became really distraught and
bored. It suddenly came to me that before we can actually save money to buy a place, I may constantly need to do this this search once in a while. Why not try to build some simple
command line tool to help me scrap down info from the website and generate a list of apartments for me? I am new to web crawlers and I have only one week before I have to find a good place to live, but I believe I can do it because 1) there are already some great
web crawling framework out there like Scrapy 2) For this year, I probably need to rent
an apartment instead of some room in a house to accommodate the occasional visit of my parents or nannies for my baby. The first reason greatly reduces my work since I don't need to reinvent the wheel. The second part limits the ranges for my search, I probably don't need to make complex search across multiple websites for now and instead I can focus on more structured websites like apartments.com or zillow for example. For my specific usage, apartments.com is better since it is neater and may contain only apartments. With the data source selected now I started to look for resources online to start my work.  </p>


<h3>Step 1: Build the Web Crawler</h3>

<p>I used python and <a href="https://scrapy.org/">Scrapy</a> to create the Web Crawler since they are relatively straight forward to use and can achieve what I need quickly.</p>

<p>Scrapy can be easily installed through
{% highlight bash %}
pip install scrapy
{% endhighlight %}
</p>
