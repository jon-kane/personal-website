---
title: Comparing Median Earnings & Home Prices in the US
author: R package build
date: "April 22, 2022"
slug: comparing-median-earnings-home-prices-in-the-us
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2022-04-22T14:29:08-05:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---



With all the craziness recently with housing costs, I became interested in looking into this. Data on median income was collected from the [US census website](https://www.census.gov/data/data-tools.html) while the housing data came from [Zillow](https://www.zillow.com/research/data/). Zillow refers to its data as the “typical” (not median) cost of a house. See [here](https://www.zillow.com/research/zhvi-user-guide/) for more info.







<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-5-1.png" width="672" />

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-6-1.png" width="672" />

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-7-1.png" width="672" />

Highlight the outliers, the US as a whole, Mississippi, and Tennessee.



Percent change from 1996 to 2018 for highlighted regions


## Some Key Takeaways
From 1996-2018, the US as a whole has experienced a 22% increase in the ratio of housing cost to median income. During the same period, CA experienced an 89% increase, Tennessee experienced a 3% increase, and MS experienced a 1% increase.


Add highlights to the base plot.

## House to median income ratio
<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-10-1.png" width="672" />

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-11-1.png" width="672" />

**Note: Montana, New Mexico, North Dakota, and Wyoming are missing data for 1996.**

### How many states (including D.C., excluding missing states) are below the national average in percent change?

```
## # A tibble: 1 × 3
##   number_above number_below proportion_below
##          <int>        <int>            <dbl>
## 1           15           32            0.681
```
## Percent change map
<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-13-1.png" width="672" />
