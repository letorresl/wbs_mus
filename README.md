# README #

Scrapy crawler that collects electricity bill amount from

https://myutilityscore.com

### Dependencies ###

This crawler is tested to work under Python 2.7.

Required dependencies to make this package run are:

-

You can install this dependent package with the following command:

pip install 

### Execution ###

You can run this scrapy crawler typing:

scrapy crawl mus -o file.csv -t csv

The previous command will output to a *.csv file

### Settings ###

This crawler is configured to cache pages for 60 minutes. You can change
this behaviour by editing the 89 line in settings file:

mus/settings.py

Or disable caching by adding a # in the start of the line.

### Contact ###

Author: Luis Torres

* luis.e.torreslopez [at] gmail.com
* github.com/letorresl
