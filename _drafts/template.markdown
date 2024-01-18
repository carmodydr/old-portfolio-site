---
layout: post
title: Title
excerpt: Some words.
tags: tag1 tag2
---

# Header

## Subheader

### Category

Data sources:

Historical Resident Population, City/County of Los Angeles, 1850 to 2010
http://www.laalmanac.com/population/po02.htm
http://www.laalmanac.com/population/

not much data, simple table format, no need to scrape
copy, paste,
(this created a bit of trouble with hidden characters)

remove ',' with :%s/,//g

Grab code from http://bl.ocks.org/mbostock/3883245 (simple line chart)

change the yrange: y.domain([0, d3.max(data, function(d) { return d.close; })]);

for some reason the extent function was returning the appropriate limits. In this case I just went in and manually edited the domain, but this is far from ideal.


[hyptertext]: link
