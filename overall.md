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

It is a well known fact that there are differences between actors and actresses ages. We wanted to test if this is true. On the barplot we can observe it and a t-test was made to check if the difference was significative. A p-value inferior to 0.5 was found indicating that actresses are in average younger than actors.

{% include Age_and_gender.html %}

# Womens representation in different genres

Next, we wanted to know how women are represented in different genres. In order to answer this question, we took a look at the twenty biggest genres in our dataset, so the genres where we have most data on actors and actresses in general. Then, we calculated the percentage of women in these genres and the result is shocking: female actresses never make up mroe than 40%, not even in romcoms! 




