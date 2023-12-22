---
layout: page
title: Movie summaries analysis
subtitle: Analysis of the words in the summaries of the movie dataset
---

Now that we have explored a bit the proportion of women in movies we were wondering how they were described and if the way they were described differed a lot between men and women. To do so we analysed the words of the movie summaries using a bag of words (machine learning) on the movie summaries. As words carry lots of information. Once the model was trained we were able to compare words that were more similar to women and others which were more similar to men. 
Firstly we look at the adjectives the most used to describe women and how different they are between women and men. Secondly we wanted to see if women were associated to different than men and if so which job it was. Finally we did a sentimental analysis to observe whether women were described with more intense sentiments than men.

# Adjectives analysis


We detected words that are adjectives in our datasets.
![Adjectives with differences](figures/wordcloud_adjective_50.png)

{% include female_words_bar.html %}

{% include male_words_bar.html %}
# Jobs analysis

![Occupation that are most different between men and women](figures/wordcloud_occupations.png)
# Sentimental analysis
