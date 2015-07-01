---
title       : Transparenz und Reproduzierbarkeit im Datenjournalismus
subtitle    : Beispiele mit R
author      : Timo Grossenbacher
job         : Datenjournalist @srfdata
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
revealjs:
  theme: simple
  transition: none
  center: "true"
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Transparenz und Reproduzierbarkeit im Datenjournalismus
### Beispiele mit R

Timo Grossenbacher, SRF Data

[@grssnbchr](http://twitter.com/grssnbchr)

[@srfdata](http://twitter.com/srfdata)

--- 

## Slide 2


```r
summary(iris)
```

```
##   Sepal.Length    Sepal.Width     Petal.Length    Petal.Width   
##  Min.   :4.300   Min.   :2.000   Min.   :1.000   Min.   :0.100  
##  1st Qu.:5.100   1st Qu.:2.800   1st Qu.:1.600   1st Qu.:0.300  
##  Median :5.800   Median :3.000   Median :4.350   Median :1.300  
##  Mean   :5.843   Mean   :3.057   Mean   :3.758   Mean   :1.199  
##  3rd Qu.:6.400   3rd Qu.:3.300   3rd Qu.:5.100   3rd Qu.:1.800  
##  Max.   :7.900   Max.   :4.400   Max.   :6.900   Max.   :2.500  
##        Species  
##  setosa    :50  
##  versicolor:50  
##  virginica :50  
##                 
##                 
## 
```

--- #slide-tweet

## Warum Transparenz?

<blockquote class="twitter-tweet" data-conversation="none" data-cards="hidden" data-partner="tweetdeck"><p lang="de" dir="ltr"><a href="https://twitter.com/brenntr">@brenntr</a> <a href="https://twitter.com/fljan">@fljan</a> <a href="https://twitter.com/srfdata">@srfdata</a> <a href="https://twitter.com/srfnews">@srfnews</a> sag ich doch, das mit dem Datenjournalismus ist eine heikle Sache und mündet zu oft in Pseudoobjektivität</p>&mdash; Jacqueline Badran (@JayBadran) <a href="https://twitter.com/JayBadran/status/613021865007820800">June 22, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>


