---
title: "Case Study: Insights from Analysing 9 Niches on Fiverr"
subtitle: ""
image: https://res.cloudinary.com/jenslaufer/image/upload/c_scale,w_456/v1555067614/9niches.jpg
image_caption: "Photo by HENCE THE BOOM on Unsplash"
output: 
  html_document: default
  md_document: default
---










You know that Fiverr is making some sellers good money. Everything about graphic design, Writing and web design seem to have a high potential. That's what our gut feeling says and what we can see, when we visit the Fiverr website. 

- However, which one of the niches makes the sellers the most money? 
- How much competition is in each niche? 
- Is it difficult to enter these niches?

We evaluated 9 niches with real data from Fiverr to answer the questions in this case study.


We entered the numbers game for these niches:

- Voiceover
- Copywriting
- Resume Writing
- Press release Writing
- Video Marketing
- Website Building
- Mobile App Development
- Graphic Design
- SEO

## Demand

We counted the total number of reviews on the first search page to get an idea of the demand. "Voiceover" has the highest demand followed by "Graphic Design" and by "SEO". The demand for "Mobile App Development", "Video Marketing" and "Press Release Writing" is much lower. It doesn't mean that these niches are uninteresting because there might be room for new Gigs. It's surprising that the demand for "Mobile App Development" is so low; we thought that Fiverr is the to-go-platform for programming tasks.

![plot of chunk unnamed-chunk-3](/figure/source/2019-04-02-insights-from-9-niches-on-fiverr/unnamed-chunk-3-1.png)



## Revenue

We aggregated a new metric for the revenue potential. We multiplied the starting price of a gig with its number of reviews.  It is not an exact estimation of what you can earn, but the metric lets us compare the revenue potential of the niches. Sellers offering "SEO", "Voiceover" and "Website Building" seem to make the most money. It's surprising that sellers offering "Graphic Design" are making much less money although there was a high demand for it. The starting prices are low here. It could be that there is much competition in this niche. On the other hand  website builders make good money. Although the demand is not so high, you can charge more in this niche.

![plot of chunk unnamed-chunk-4](/figure/source/2019-04-02-insights-from-9-niches-on-fiverr/unnamed-chunk-4-1.png)



## Supply

We checked the supply for the niches by taking the number of Gigs for the niche keywords. It's interesting that there are so many gigs for "Mobile App Development" although the revenue potential is not so high. There are also many Voice-Over-Artists and SEO consultants in the market, but you can earn good money in the niches. Interesting is that there are just a few copywriters on Fiverr, although the revenue potential is not bad.

![plot of chunk unnamed-chunk-5](/figure/source/2019-04-02-insights-from-9-niches-on-fiverr/unnamed-chunk-5-1.png)

## Competition

We mix the demand and supply to get an idea of how much competition is in the niche markets. You can see something we saw already before; there is not that much competition in the market for copywriters and for Video marketers, which is unexpected. On the other, the market for "Mobile App Developers" is very tough. 

![plot of chunk unnamed-chunk-6](/figure/source/2019-04-02-insights-from-9-niches-on-fiverr/unnamed-chunk-6-1.png)

## Market Entry Barrier

Another metric is the entry market barrier, which describes how difficult it is to rank on the first page of the search page. It is influenced by the competition, but also by algorithms that Fiverr uses to decide which gig is on page one. We aggregated the ratio of unrated Gigs on the first search page for this. The higher the percentage of unrated gigs the easy it is to get to search page one, which helps you to get a share of the pie. 

The barrier to enter the market is the easiest for "Press Release Writing" and "Mobile App Development". It's very interesting that it seems easy to enter the "Website Building"-market, which has good revenue potential. On the one hand, it is but very difficult to get into "Graphic Design".

![plot of chunk unnamed-chunk-7](/figure/source/2019-04-02-insights-from-9-niches-on-fiverr/unnamed-chunk-7-1.png)



## Overall Rank


We created an overall rank to combine the metrics revenue potential, competition and market entry barrier. The three metrics are weighted differently. The revenue potential goes 50% into the parameter, the competition is weighted 30% and the market entry barrier 20%. We have the highest score for "SEO", "Voiceover" and "Website Building". They are the top 3 here.


![plot of chunk unnamed-chunk-8](/figure/source/2019-04-02-insights-from-9-niches-on-fiverr/unnamed-chunk-8-1.png)








