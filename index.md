---
title       : Data Products Project Pitch in Slidify
subtitle    : 
author      : D
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Why this deck ?

1. I love the possibilities of Shiny and deploying R code into an interactive enviroment for my info users
2. So, I am focussing this exercise as a training into how the user interactivity works.
3. Use an empty line followed by three dashes to separate slides!

--- 

## Why this content ?

1. I love the ability of Shiny to distribute R results in an interactive fashion with my info users
2. So, I wanted to use this exercise to focus on figuring out to see how to unlock R-data in shiny.


--- 

## So what did I do ?

1. I used the mtcars example and built it part by part to figure out what part does what
2. Then rewrote it to run for the iris database, just as a proof of concept.


--- 

## What is next ?

1. Now that I figured out how to make this work, technically, can start thinking about my regular reporting items and build them in shiny

--- 

## Bonus slide

The instructions required 5 slides with some r-code to be evaluated, so here it is:


```r
data(iris)
attach(iris)
## this is the structure of the used dataset:
str(iris)
```

```
## 'data.frame':	150 obs. of  5 variables:
##  $ Sepal.Length: num  5.1 4.9 4.7 4.6 5 5.4 4.6 5 4.4 4.9 ...
##  $ Sepal.Width : num  3.5 3 3.2 3.1 3.6 3.9 3.4 3.4 2.9 3.1 ...
##  $ Petal.Length: num  1.4 1.4 1.3 1.5 1.4 1.7 1.4 1.5 1.4 1.5 ...
##  $ Petal.Width : num  0.2 0.2 0.2 0.2 0.2 0.4 0.3 0.2 0.2 0.1 ...
##  $ Species     : Factor w/ 3 levels "setosa","versicolor",..: 1 1 1 1 1 1 1 1 1 1 ...
```
