# Experimentation & Personalization Step-by-step guide with Google Optimize and Google Analytics

1. [Getting started](#getting-started)
2. [Experimentation](#experimentation)
3. [Testing and reporting](#testing-and-reporting)
4. [Personalization](#personalization)

The goal of this article is to serve as guide to get you started on Optimize for exprimentation and personalization. For the purpose of the demo I will be using a [demo site](https://ekarttr.github.io/optimize-demo/index.html) that I got my hands on (I don't know who created the demo site, but whoever you are - thank you!) to demonstrate experimentation and personalization using Google Optimize along with Google Analytics.

## 1. Getting Started

### Create an experiment
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img11.png?raw=true">

### Create an A/B test

An A/B test is a randomized experiment using two or more variants of the same web page (A and B). Variant A is the original and variant B through n each contain at least one element that is modified from the original. [Read more] (https://support.google.com/optimize/answer/6211930?hl=en) about A/B tests.

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img12.png?raw=true">

## 2. Experimentation

Before diving into your first experiment you should identify a problem and create a hypothesis that's backed up by data. Start by identifying a problem that you want to solve. [Read more](https://support.google.com/optimize/answer/6211930?hl=en) 

### Create a variant by changing text, editing HTML or even removing links

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img1.gif?raw=true">

### Create a variant by resizing and moving content 

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img2.gif?raw=true">

### Set up objectives
Objectives are an integral part of creating an experiment that determine how your variants perform and inform the statistical model used to pick leaders. Think of objectives as the metrics or activities that your variants are measured against.
Think of your experiment's objective as "the website functionality you wish to optimize." Common objectives for publishing websites are pageviews and subscriptions, while ecommerce websites tend to use objectives like revenue and conversions.
[Read more](https://support.google.com/optimize/answer/7018998?hl=en) about objectives here.

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img3.gif?raw=true">

### Selecting a custom objective
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img13.png?raw=true">

### Audience targeting using query parameters

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img4.gif?raw=true">

Query parameter 1 = utm_source, variable = src_var, src_var = example.com. This corresponds to: 
[URL?utm_source=example.com](https://ekarttr.github.io/optimize-demo/index.html?utm_source=example.com)

Query parameter 2 = utm_medium, variable = med_var, src_var = referral. This corresponds to:
[URL?utm_medium=referral](https://ekarttr.github.io/optimize-demo/index.html?utm_medium=referral) 

This will ensure that only traffic coming from example.com as a referral (assuming the traffic is tagged properly) will be included in the experiment. The final URL that was used to test corresponds to: [URL?utm_source=example.com&utm_medium=referral](https://ekarttr.github.io/optimize-demo/index.html?utm_source=example.com&utm_medium=referral) 

### Google Analytics audience targeting (Optimize 360 feature)
This feature is only available in Google Optimize 360, [part of Google Marketing Platform] (https://marketingplatform.google.com/about/).

Audience targeting is useful for targeting high-value customers with special offers and incentives or loyal customers with an email signup. You can target users interested in a specific product category to see if a customized home page increases conversions. You can also create Audiences in Google Analytics for users who have converted recently, who convert frequently, or who spend a lot of time on your website, and then target them from within Optimize. [Read more](https://support.google.com/optimize/answer/6283435?hl=en) about audiences.

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img8.gif?raw=true">

### Launch the experiment
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img5.gif?raw=true">

## 3. Testing and reporting

To monitor a running experiment or see the results of a concluded experiment, click the Reporting tab at the top of the experiment detail page. You can also view your results in Google Analytics. [Read more](https://support.google.com/optimize/answer/6218117?hl=en) about reporting.

### Test the experiment
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img9.gif?raw=true">

### Reporting in Optimize
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img7.png?raw=true">
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img6.png?raw=true">

### Reporting in Google Analytics 
<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img14.png?raw=true">

## 4. Personalization

Optimize enables you to run website experiments to determine what converts best with your visitors. Once you discover what's relevant to their interests – and what's most likely to achieve your objectives – Optimize can serve personalized experiences that promote engagement and improve conversions.

Optimize allows you to:

1. Test a hypothesis by running website experiments.
2. Deploy the leading variant permanently.
3. Personalize your website to create the best experience for your visitors.

[Read more] (https://support.google.com/optimize/answer/9112930?hl=en) about personalization. 

<img src="https://github.com/ekarttr/optimize-demo/blob/master/img/img10.gif?raw=true">

### References:
1. Google Optimize Support: https://support.google.com/optimize/
2. Google Marketing Platform: https://marketingplatform.google.com/about/

 
