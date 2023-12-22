---
layout: page
title: Exploring gender differences in cinema
subtitle: by ADAvengers2023
cover-img: /assets/img/eatpraylove.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/eatpraylove.jpg
tags: [books, test]
author: İrem Şekeroğlu, Ariane Augustoni, Caroline Vonmering, Heling Shi, Shu Yang
---
Our project aims to critically examine the portrayal of female characters in cinema. Driven by the movies‘ profound cognitive influence, our objective is to explore how depictions of women evolve with time and to identify any existing biases or subtle forms of discrimination.

To achieve this, we will investigate the differences in commonly used adjectives that appear alongside male or female characters in movie summaries. We will also study the characteristics of female characters across different movie genres, tracing how their portrayals have transformed in line with the rising tide of the feminist movement.

This study is fueled by the increasing societal focus on gender representation in media. By scrutinizing historical and character-level data, we aim to reveal trends in the depiction of women in film, thereby mirroring broader societal shifts.

Our dataset comes from the CMU [Movie Summary Corpus](https://www.cs.cmu.edu/~ark/personas/)

# Some general observations

It is a well known fact that there are differences between actors and actresses ages. We wanted to test if this is true. On the barplot we can observe it and a t-test was made to check if the difference was significative. A p-value inferior to 0.5 was found indicating that actresses are on average younger than actors.

{% include Age_and_gender.html %}

# Womens representation in different genres

Over all movies together, we can see that there are more male actors than female actresses. 

{% include Gender_proportion.html %}

Next, we wanted to know if the genre has an impact on that. How are women represented in different genres? In order to answer this question, we took a look at the twenty biggest genres in our dataset, so the genres where we have most data on actors and actresses in general. Then, we calculated the percentage of women in these genres and the result is shocking: female actresses never make up more than 41.5%, not even in romcoms! And in action movies, the percentage of women falls below 25%. This difference in the amount of women in different genres is highly significant: We perforemd a chi-squared test and obtained a p-value of approximately zero. 

{% include Genres_Pink_2.html %}

# Women playing different character types

We were further interested which character types women play most often in the movies. We can see that women are most prevalent in the character types "dumb blonde" and "brainless beauty". We can also see that there is a big disproportionality in the number of character types for men and for women. This can partly be explained by the surplus of data on men than on women. But it might also hint at the fact that there are fewer "boxes" for female characters to fit in, they are portrayed more stereotypically and there is less variety in how they are written. Either way, the effect of character types on gender is significant, we performed a chi-square test and got a p-value of 5.59e-42. 


{% include types_wholeplot.html %}


Do you want to know more about with which adjectives male and female characters are described, which sentiments are linked to them, and what jobs they usually have in movies? You can find all that and more here. (add summaries link)
[Click here to learn more about summaries](/Women_and_movies/summaries/)


