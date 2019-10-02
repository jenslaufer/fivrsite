---
title: "Is it possible to make a million on Fiverr?"
subtitle: "Insights from analysing Fiverr data to answer the question"
categories:
  - blog
image: https://res.cloudinary.com/jenslaufer/image/upload/c_scale,w_456/v1554277064/ishan-seefromthesky-562756-unsplash.jpg
image_caption: "Photo by Ishan @seefromthesky on Unsplash"
output: 
  html_document: default
  md_document: default
  
params:
  # filter: '{"keyword": {"$in": ["airbnb", "alibaba", "amazon", "amazon fba", "data analysis", "data science", "fiverr", "java programming", "market analysis", "market research", "passive income", "python programming", "r programming", "reporting" , "scraping", "six figures"]}}'
  filter: '{"keyword": {"$in": ["Voiceover", "Copywriting", "Resume Writing", "Press release Writing", "Video Marketing", "Website Building", "Mobile App Development", "Graphic Design", "seo"]}}'
---






























The story of [How a dad made almost 1 million on Fiverr](https://www.cnbc.com/2018/04/24/how-this-dad-made-almost-1-million-on-fiverr.html?__source=msn%7Cmoney%7Cinline%7Cstory%7C&par=msn&doc=105300315) inspired us to analyse real data from Fiverr to gain insights on how realistic a story like this is. First, we were looking for more stories from people to get an idea of what they earn and what they are doing. 

| Seller | Type of service | Income |
| ------ | --------------- | -----: |
| [Joel Young](https://www.cnbc.com/2018/04/24/how-this-dad-made-almost-1-million-on-fiverr.html?__source=msn%7Cmoney%7Cinline%7Cstory%7C&par=msn&doc=105300315)| Voice Over | $1,000,0000|
| [Charmaine Pocek](https://www.forbes.com/sites/laurashin/2016/05/31/how-these-3-people-make-6-figures-a-year-on-fiverr/)| Resume writing | $480,000|
| [Levi Newman](https://www.forbes.com/sites/laurashin/2016/05/31/how-these-3-people-make-6-figures-a-year-on-fiverr/)|Copywriting| $180,000 |
| [Redd Horrocks](https://www.forbes.com/sites/laurashin/2016/05/31/how-these-3-people-make-6-figures-a-year-on-fiverr/)|Voice Over| $180,000 |
| [Alex Fasulo](https://www.msn.com/en-us/money/bills-to-pay/how-this-25-year-old-freelancer-made-dollar150000-in-6-months-off-fiverr/ar-AAzkNOA)| Press Release Writing | $150,000 |
| [David Feldman](https://www.cnbc.com/2018/12/18/how-this-38-year-old-is-making-6-figures-freelancing-on-fiverr.html)|Copywriting|$100,000|

These numbers are impressing! It looks like an attractive business model.

## Are these sellers exaggerating?

We are in a world of self-marketing, everybody wants to get on page one with his story to push his business. Why not cheat a bit with the numbers? We fetched real data from Fiverr to get an idea of how realistic the numbers are.

First, we identified the usernames of the sellers, which was not difficult. Then we extracted the data for the gigs these sellers are offering. You can retrieve the price, and you can see the number of reviews, which lets you calculate a metric "reviewed revenue". Afterwards, you can add up the revenue for all gigs somebody is offering to get an impression of the seller's total revenue.



![plot of chunk unnamed-chunk-7](/figure/source/2019-03-27-is-it-possible-to-earn-1-million-on-fiverr/unnamed-chunk-7-1.png)

The reviewed revenue of David Feldman, Joel Young and Alex Fasulo is lower than the income reported in the stories. The reviewed revenue is by a factor between 0.3 and 0.5 lower. On the other hand, for Redd Horrocks, Levi Newman and Charmaine Pocek the reviewed revenue is by a factor between 1.3 and 1.8 higher than the reported income.

So our first impression could be: We caught all of them on lying and David, Joel and Alex are terrible exaggerators.

This view is a bit too simplified. We were curious what's the rated order ratio is on Fiverr. We found a post on the Fiverr forum on it: [What is your Rated Orders percentage?](https://forum.fiverr.com/t/what-is-your-rated-orders-percentage/143919/6) and we asked the sellers on Reddit for their [rated order ratio](https://www.reddit.com/r/Fiverr/comments/b8h1pn/help_what_is_your_rated_order_ratio/). People report ratios at around 80%, which seemed very high to us. We decided to take a value of about 50%. With this ratio the revenues of Alex, Joel and David seem realistic (no liers). It means on the other hand that Redd, Levi and Charmaine are making much money than they reported. 

We calculated the realistic revenue numbers for the sellers with a rated order ratio of 0.5

![plot of chunk unnamed-chunk-8](/figure/source/2019-03-27-is-it-possible-to-earn-1-million-on-fiverr/unnamed-chunk-8-1.png)

With this estimation, we can see that Joel Young and Charmaine Pocek are most probably made over million on Fiverr. But also Levi Newman and Redd Horrocks are making quite a bit of money.


## What gigs?

What gigs are making this amount of money? We evaluated the Top 3 gigs for each of our friends. 



![plot of chunk unnamed-chunk-9](/figure/source/2019-03-27-is-it-possible-to-earn-1-million-on-fiverr/unnamed-chunk-9-1.png)

It impresses that Charnine Pocek 'I will Create An Entry Level Resume, Cv, Cover letter, Or LinkedIn' made at least 500,000. Her 'I will Upgrade A Resume, Cv, Cover letter, Or LinkedIn" gig made over 250,000 so far. Joel Young's 'I Will Create A Whiteboard Animation Video' filled his bank account with at least 350,000. Redd Horrocks 'I will Record A Quality Voiceover, British Or American Accent' made over 200,000 so far, as well as Levi Newman's 'I Will Create A Professional Amazon Product Listing Audio File'.

This is unbelievable: One single gig is making over 500,000.

But is this realistic to everybody of us?

## Can everybody be a superstar?

Can everybody make 500k  with one single Gig?

We analysed 2634 Gigs in 57 niches to answer this question:

Are there other gigs that made over a 100,000 reviewed revenue?

![plot of chunk unnamed-chunk-10](/figure/source/2019-03-27-is-it-possible-to-earn-1-million-on-fiverr/unnamed-chunk-10-1.png)

This shows you that more people are making a ton of money on Fiverr.


## How realistic is it to make your first million on Fiverr?



![plot of chunk unnamed-chunk-11](/figure/source/2019-03-27-is-it-possible-to-earn-1-million-on-fiverr/unnamed-chunk-11-1.png)

You can see that the majority of Gigs made less than 1,000. Reaching between 1,000-10,000 is possible, but everything over that is quite hard to achieve.

## Conclusion

We answered the question if it is possible to make 1,000,000 on Fiverr. We could prove that it is possible and that there are even more superstars on Fiverr who are making a lot of money. But we also learned earning these amounts is a tough job.

It's maybe a good idea to find more superstars and learn from them.

Do you want to __Find a profitable niche & Dominate Fiverr__? 

Then check out the Gig [Fiverr Niche Analysis](https://www.fiverr.com/jens_laufer/do-a-niche-analysis-on-fiverr)
