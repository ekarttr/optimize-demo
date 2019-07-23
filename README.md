# Hands-on Experimentation Guide with Google Optimize 

1. [Getting started with an experiment](#create-variants-you-wish-to-experiment-with)
2. [Creating variants to test](#create-variants-you-wish-to-experiment-with)
3. [Testing the experiment](#create-variants-you-wish-to-experiment-with)
4. [Personalization with Google Optimize](#create-variants-you-wish-to-experiment-with)

The goal of this article is to serve as guide to get you started on Optimize for exprimentation and personalization. For the purpose of the demo I will be using a [demo site](https://ekarttr.github.io/optimize-demo/index.html) that I got my hands on (I don't know who you are, but thank you for the the demo site!) to demonstrate experimentation and personalization using Google Optimize along with Google Analytics.


### Create an experiment
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img11.png?raw=true">

### Create an A/B test

An A/B test is a randomized experiment using two or more variants of the same web page (A and B). Variant A is the original and variant B through n each contain at least one element that is modified from the original. (Read more) [https://support.google.com/optimize/answer/6211930?hl=en].

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img12.png?raw=true">

## Create variants to test

### Variant 1: Change text, edit HTML, remove links

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img1.gif?raw=true">

### Variant 2: Resize and move content 

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img2.gif?raw=true">

### Set up objectives

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img3.gif?raw=true">

### Selecting a custom objective
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img13.png?raw=true">

### Audience targeting using query parameters

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img4.gif?raw=true">

Query parameter 1 = utm_source, variable = src_var, src_var = example.com
Sample URL: https://ekarttr.github.io/optimize-demo/index.html?utm_source=example.com 

Query parameter 2 = utm_medium, variable = med_var, src_var = referral
Sample URL: https://ekarttr.github.io/optimize-demo/index.html?utm_medium=referral 

This will ensure that only traffic coming from example.com as a referral (assuming the traffic is tagged properly) will be included in the experiment. 

The final URL that was used to test: https://ekarttr.github.io/optimize-demo/index.html?utm_source=example.com&utm_medium=referral 

### Google Analytics audience targeting (Optimize 360 feature)
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img8.gif?raw=true">

### Launch the experiment
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img5.gif?raw=true">

### Test the experiment
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img9.gif?raw=true">

### Reporting in Optimize
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img7.png?raw=true">
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img6.png?raw=true">

### Reporting in Google Analytics 
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img14.png?raw=true">

## Personalize
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img10.gif?raw=true">




 
