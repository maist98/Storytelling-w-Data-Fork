# Pittsburgh: A Fast Food Desert

## Introduction

When people think about deserts, they think about a place that is lacking. While Pittsburgh doesn't suffer from a lack of rain it does suffer from a lack of something else: **food**. Now, I'm not saying that you'll starve in Pittsburgh - the adult obesity rate is over 34% (Pittsburgh Quarterly) and restaurants dot  the city like spots on a leopard. But what I am saying is that if you want to find the quintessential staple of American cuisine, that is, fast food, you'll be out of look.

* **One Line Summary:** Pittsburgh has a shortage of fast food restaurants relative to other metropolitan areas
* **For the Audience:** I want the audience to care about fast food, particularly its absence in Pittsburgh
* **Call to Action:** I want the audience to sympathize or possibly even support my idea to build a McDonald's 2 blocks away from my apartment

## Outline

* Introduction of the topic
  * Define what fast food is
  * Summarize my topics

* Why it's important
  * Visualization #1 (icons): Cost of a meal (including drinks) at various fast food restaurants vs other restaurants
  * Visualization #2 (bar graph): Median income of US vs Pittsburgh

* National Outlook
  * Visualization #3 (interactive hex map): # of fast food restaurants by state
  * Visualization #3a: Call out the state of Pennsylvania
  
* Narrow in on Pittsburgh
  * Visualization #4 (bar graph): # of fast food restaurant by metropolitan city (Pittsburgh, Denver, Philadelphia, Boston, NYC, Chicago, etc)
  * Visualization #5 (bar graph): # fast food restaurant by area
  * Visualization #6 (bar graph): # of people per fast food restaurant

* Call to action
  * Visualization #7 (map): map of Pittsburgh of fast food locations
  * Propose a new location Downtown [McDonald's Franchise Link](https://www.mcdonalds.com/us/en-us/about-us/franchising/franchising-form.html?cid=GA:USSF:USSF6:PPC-C::PPC&utm_term=mcdonalds%20franchise&utm_campaign=McDonalds+Franchise+Campaign+-+Conversion&utm_source=adwords&utm_medium=ppc&hsa_acc=9078027113&hsa_cam=20796188043&hsa_grp=157624513324&hsa_ad=755965563113&hsa_src=g&hsa_tgt=kwd-32225096&hsa_kw=mcdonalds%20franchise&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=20796188043&gbraid=0AAAAAqddkVLhWD-kbApZcrjH61QyiKJ68&gclid=Cj0KCQjwrc7GBhCfARIsAHGcW5Up_R8Q1FH-9dH4aPQ-EwPn_HLueCzhlr9dhZ2JgxJ6zMtekaYzpDAaAltGEALw_wcB)
    
## Initial Sketches

**Dot Plot to compare cost of an average meal. I want to add icons to the callouts in the actual viz.**

<img src="Viz 1.JPG" width="300"/>

**Bar graph to compare incomes.**

<img src="Viz 2.JPG" width="300"/>

**Hexmap with gradient to show # of restaurants per state. I think I want to change the color to something else.**

<img src="Viz 3.JPG" width="300"/>

**The following bar graphs just provide basic data. I think I need to spice them up with a summary sentence.**

<img src="Viz 4.JPG" width="300"/>

<img src="Viz 5.JPG" width="300"/>

<img src="Viz 6.JPG" width="300"/>

**A very poorly drawn map of Pittsburgh. I plan on plotting all the fast food restaurants in Pittsburgh before proposing a new location.**

<img src="Viz 7.JPG" width="300"/>

## The Data

To construct this story, I plan on using disparate sources of data and synthesizing elements from the data sets to create each element of my story. 

I'll have to do some brief menu research to find the cost of an average meal at certain restaurants. This will likely be the most tedious depending on how many restaurants I want to display and finding a meal that is comparable to one another. I think this vital in order to portray a benefit to fast-food. I am aware that most people are biased against fast-food and would harbor ill-will to my endeavor. I must convince them that there is a meaningful gain to my endeavor.

For the median income, I found another [link](https://www.census.gov/library/visualizations/interactive/median-household-income.html) to the US Census Bureau that provides median income by county. This will help me emphasize that Pittsburgh residents have a need for fast-food since it is a relatively cheap meal.

For the fast food restaurant data, I've found a usable data set of fast-food restaurants across America on [Kaggle](https://www.kaggle.com/datasets/imtkaggleteam/fast-food-restaurants-across-america). I will adjust the data since it includes some restaurants (like Chipotle) that I (and Google AI) consider fast-casual. I believe it is vital to show the distribution of fast-food restaurants around the country in order to provide context for the trends in other areas that I will be comparing Pittsburgh to.

For the population data, I found a [link](https://www2.census.gov/programs-surveys/popest/datasets/2020-2024/counties/totals/co-est2024-alldata.csv) to the US Census from 2024 which I can use to help determine population density of specific regions or cities. This is incredibly convenient since it "should" already takes into account the fact that Pittsburgh is a college town; the census counts resident college students in the county they physically reside in. This will provide the framework that Pittsburgh doesn't have enough fast-food restaurants to serve its population.

To get the city sizes, I'll have to do some brief Googling on whatever cities I want to display. This will help ground my argument; instead of pointing to existential reasons, I can point to a physical manifestation of Pittsburgh's lack of fast-food. 

Lastly, I plan on using either Google Maps or Apple Maps to display the fast food restaurants in Pittsburgh in order to pinpoint a suitable location for my call to action.

## The Medium

For now, I'm planning on using Tableau to compile my maps however I may use some other software if Tableau isn't user-friendly enough. I'll create a new Shorthand website to tell my story. Since I need to convince the audience that this endeavor is worthwhile, I want to make the website evoke feelings of nostalgia.

**Initial Feedback:** I received positive feedback from my peers about this project. However, it was suggested that I consider narrowing the scope; I could compare the counties of Pittsburgh instead of Pittsburgh against other metropolitan areas. Additionally, since my call to action is specifically for McDonald's I could focus on an alternate dataset that only includes McDonalds [Link](https://www.kaggle.com/datasets/jacopomazzoni/mcdonalds-locations-2025). Depending on how the dataset looks, I might do that since it aligns a little more with my call to action.

## Sources

https://www.kaggle.com/datasets/imtkaggleteam/fast-food-restaurants-across-america

https://www2.census.gov/programs-surveys/popest/datasets/2020-2024/counties/totals/co-est2024-alldata.csv

https://www.census.gov/library/visualizations/interactive/median-household-income.html

https://www.ers.usda.gov/amber-waves/2018/june/higher-incomes-and-greater-time-constraints-lead-to-purchasing-more-convenience-foods
