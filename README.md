# Project: Investigate a Dataset - TMDb Movie Data

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
    <ul>
    <li><a href="#question1">WHAT PROPERTIES CAN BE GOOD INDICATORS OF HIGH REVENUE MOVIES?</a></li>
    </ul>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='intro'></a>
## Introduction

### Dataset Description  

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.


### Question(s) for Analysis
>**Question One**: WHAT PROPERTIES CAN BE GOOD INDICATORS OF HIGH REVENUE MOVIES?

<a id='eda'></a>
## Exploratory Data Analysis

<a id="question1"></a>

### WHAT PROPERTIES CAN BE GOOD INDICATORS OF HIGH REVENUE MOVIES?

We are going to investigate the correlation of:

* `` popularity ``
* `` vote_average ``
* `` vote_count ``
* `` budget_adj``
* `` revenue_adj``
* `` runtime ``

with the returns the movies.

we are going to check if the following properties have a positive correlation and how many point will be found close to the line-of-best-fit.

we will be checking this properties on groups of high earning movies:

<ul>
<li><a href="#10">Top 10</a></li>
<li><a href="#1000">Top 1000</a></li>
<li><a href="#10000">Top 10000</a></li>
<li><a href="#all">All Sorted Movies</a></li>
</ul>

<a id='conclusions'></a>
## Conclusions

   After we have checked the properties in the data set, we have found out that:
   
   * `` popularity``
   * `` vote_average ``
   * `` vote_count ``
   * `` revenue_adj``
        
are good indicators of high earning movies since it show how the fans of the movies have recieved it.
    
   We also experiences limitation such as:
   > **1**: Not all rows of genres and imdb_id we filled and thus, we had to drop them, they may be small but when analysing earnings/returns, each movie has a specific amount associated with it.
        
