![Houses](/udacityhouseprices/docs/assets/houses.jpg)
## Introduction

Eventuelly at some point in your life.  You will hassle with yourself if you want to buy a house and if so what kind, how big, what are the features and what will it cost me. This is exactly the turning point where I am right now.

You may have the feeling "Oh this property is expensive", or "Castles are quite hard to find.". But this is just your own, subjective perception. So what does the data imply?
Thus I looked for a dataset regarding house prices. I came up with a good set of data which was scraped in 2020 from [Immoscout24](https://www.immobilienscout24.de/), the biggest german real estate market.

The dataset consists of 10,500 entries from all 16 German Bundesländer. The author collected 26 different features e.g. price, lot area, bedrooms, energy features and many more. The first thing I want to know is the most common house type in Germany.

# What is the most common real estate property in Germany?

Here you can see the different house types in ascending order. Even though Germany has a lot of castles, it is the least offered type of property. Who would have thought ;). The most commen type is the mid-terrace house, followed by a duplex and the single dwelling houses. So if you are looking for one of these types you will face a broad offering.

![type_hist](/udacityhouseprices/docs/assets/type_hist.png)

# Which of the 16 german federal states is the most expensive?

As you can see in the following table. The highest mean prices are achieved in Berlin & Hamburg,followed by the two economic centers Baxern & Baden-Würrtemberg.
Even the price per square meter is the most expensive in Hamburg and Berlin. 

This result is not very surprising, Hamburg & and Berlin are city-states, meaning the federal state only consists on one city. The other federal states also have quite big rural regions, which leads to a lower mean price.



| Federal State          | Price [in EUR] | Price/m<sup>2</sup> [in EUR] |
|------------------------|----------------|------------------|
|                 Berlin |      1,160,439 |            5,215 |
|                Hamburg |        835,454 |            5,076 |
|                 Bayern |        820,002 |            3,881 |
|      Baden-Württemberg |        708,397 |            3,493 |
|                 Hessen |        667,460 |            2,994 |
|            Brandenburg |        564,342 |            2,886 |
|    Nordrhein-Westfalen |        558,275 |            2,607 |
|     Schleswig-Holstein |        541,217 |            3,692 |
|                 Bremen |        429,788 |            2,855 |
|        Rheinland-Pfalz |        411,067 |            2,984 |
| Mecklenburg-Vorpommern |        410,558 |            1,993 |
|          Niedersachsen |        376,872 |            2,039 |
|                Sachsen |        323,617 |            1,476 |
|              Thüringen |        263,255 |            1,275 |
|               Saarland |        257,224 |            1,328 |
|         Sachsen-Anhalt |        204,837 |            1,121 |

*Table 1: mean prices in Euro and mean prices per square meter*


# Predicting houseprices by its features.


## Summary
In this article, we took a deeper look at the German real estate market regarding to collected data from Immoscout24 in 2020.
We saw that the most common type is the mid-terrace house. So if you are looking for one you are in luck. Furthermore you are not so lucky if you are looking for a house in Berlin or Hamburg, since they are the most expensive federal states in Germany.

So now that you are a lot smarter than before. There is only one question which remains:

**When will you buy your first real estate property?**


