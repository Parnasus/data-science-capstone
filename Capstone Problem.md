# Recommendation of London Boroughs

## Introduction

A common problem for people is to choose which area of a big city to live in - i.e. which part of the city to rent their accommodation in. One obvious and objective constraint is how expensive the area is. However, there are a lot of other subjective criteria based on personal preferrences - e.g. what kind of venues would they prefer to have close to home (shopping, bars, parks, etc.). 

In order to make this a little more manageable, a recommendation application can be built. Top five areas within a city will be identified based on parameters entered by the user :  
1. The amount rent they are willing to pay (min, max)
2. Ranking of top four venues that are the most important to them (e.g. Shopping, Green spaces, etc)

Because of availability of high quality data, I chose to implement this application for London, UK. There are 33 boroughs within the Greater London area

When choosing a location where to live in Greater London area, one usually has to rely on their friends recommendations or a (biased) internet search. Everybody's situation is different and they might care about different aspects of each borough in Greater London area. For example, some people are willing to pay more on rent and live in a more central location where they get access to lot of shops and restaurants. For the others, however, it might make more sense financially to live in the less expensive parts, but the ones that have good public transport coverage as well as decent number of going out options. 

To address this, I am building a recommender application that will help identify top three boroughs based on users parameters:  
1. The amount rent they are willing to pay (min, max)
2. The type of venues that are the most important to them (e.g. Shopping, Green spaces, etc)


The rent data is available from UK Government's data portal, while the data about various venues can be retrieved using free version of Foursquare API.