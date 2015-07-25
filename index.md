---
title       : Prediction of Titantic Survival
subtitle    : A simple model
author      :
job         :
framework   : io2012      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is it?

An algorithm which predicts the probability of a passenger surviving the Titanic using only 
four variables:
* Age
* Sex
* Cabin class
* Port of embarkation

---

## Model description and inputs

The algorithm used is a logistic regression model.  

It was trained using data avaliable from the Kaggle Titanic excercise (https://www.kaggle.com/c/titanic).

In the training set:
* Age ranged from 0 to 80
* There were 18.3980892 more males than females
* There were 2.2731481 more passengers in third class than first class
* The majority of the patients embarked at Southampton

---

## Prediction accuracy

It's a simple algorithm and requires very few inputs, yet has an estimated accuracy of 0.76

---

## Where do I find it?

Try it for yourself here:

https://betshsu.shinyapps.io/shiny-app



