---
title: "Keeping up-to-date with the literature"
author: "Danny Wong"
date: "02 May, 2018"
layout: post
blog: true
tag:
- Perioperative Medicine
- thoughts
- medicine
---

The medical literature changes so fast that it's terribly difficult to stay current. In pursuing my PhD, I've discovered that the old model of literature review -> formulate a question -> design an experiment/study -> do the study -> analyse -> write-up is terribly difficult to do in series. You constantly have to do EVERYTHING in parallel. 

Also by the time you get to the write-up stage, you realise that your literature review is horribly out-of-date! What can we do to fix this?

I've recently found out that [PubMed](https://www.ncbi.nlm.nih.gov/pubmed) has a brilliant RSS feed function. And so you can create a search of the literature base that you want to keep current with and then keep in refreshed in the background as an RSS feed. RSS stands for Really Simple Syndication. I'll walk you through getting one set up:

## 1. Create your search

Go to [PubMed](https://www.ncbi.nlm.nih.gov/pubmed) and create a search, it can be as simple or as complicated as you wish.

![Step 1: Create your search](../figures/2018-05-02-Keeping-up-to-date-with-the-literature/step1.png)

## 2. Create your RSS feed

Click on the `Create RSS` link just under the search bar.

A little configuration box will pop up. Select your settings (I chose to keep 100 articles on my feed). Then click on the `Create RSS` button.

![Step 2: Create your RSS feed](../figures/2018-05-02-Keeping-up-to-date-with-the-literature/step2.png)

## 3. Cut and paste into RSS feed reader

If you haven't already got an RSS feed reader installed. Install one. There're loads on the market. I have chosen to use an RSS feed reader that's contained within my browser (Google Chrome) as an extension. I'm using [Slick RSS](https://chrome.google.com/webstore/detail/slick-rss/ealjoljnibpdkocmldliaoojpgdkcdob?hl=en).

You can now open it up on your RSS feed reader like so:

![Step 3: RSS feed reader](../figures/2018-05-02-Keeping-up-to-date-with-the-literature/step3.png)

Quickly browse through the articles and their abstracts and click on the ones you think are relevant, and add it to your bibliography or print it out or do what you would normally to digest this information. Or maybe more realistically: file it away and let it stack up till when you have the time, if you EVER get the time.


{% highlight r %}
sessionInfo()
{% endhighlight %}



{% highlight text %}
## R version 3.4.2 (2017-09-28)
## Platform: x86_64-w64-mingw32/x64 (64-bit)
## Running under: Windows >= 8 x64 (build 9200)
## 
## Matrix products: default
## 
## locale:
## [1] LC_COLLATE=English_United Kingdom.1252 
## [2] LC_CTYPE=English_United Kingdom.1252   
## [3] LC_MONETARY=English_United Kingdom.1252
## [4] LC_NUMERIC=C                           
## [5] LC_TIME=English_United Kingdom.1252    
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
## [1] knitr_1.17
## 
## loaded via a namespace (and not attached):
##  [1] Rcpp_0.12.14     assertthat_0.2.0 dplyr_0.7.4      grid_3.4.2      
##  [5] plyr_1.8.4       R6_2.1.2         gtable_0.2.0     magrittr_1.5    
##  [9] evaluate_0.10.1  scales_0.5.0     highr_0.6        ggplot2_2.2.1   
## [13] pillar_1.2.1     stringi_1.1.7    rlang_0.2.0      lazyeval_0.2.0  
## [17] bindrcpp_0.2     anomalize_0.1.0  tools_3.4.2      stringr_1.2.0   
## [21] glue_1.1.1       munsell_0.4.3    yaml_2.1.18      compiler_3.4.2  
## [25] pkgconfig_2.0.1  colorspace_1.2-6 bindr_0.1        tibble_1.4.2
{% endhighlight %}
