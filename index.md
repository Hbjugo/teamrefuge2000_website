---
layout: page
title: Are Movies Sexist ?
subtitle: How much are movies subdued to gender stereotypes?
output: html_document
cover-img: /assets/header.png
use-site-title: true
---

With Christmas coming up very soon, you must have seen them everywhere, or they were given to you when you were a child: the oh-so-stereotyped Christmas gifts. When little girls receive baby dolls, makeup kits and fashion sketchbooks, little boys are blessed with dinosaurs, fire engines, and false hardware tools. The new generations of parents are more and more aware that these stereotyped gifts are founded on nonsense assumptions, such as “a girl’s dream is to be the prettiest” and “every boy wishes to join the army”. Moreover, it has been shown that this entire sexist mindset has led, among other consequences, to professional categories showing a very small number of women enrolled. Just look at EPFL, or any other engineering school …

With this project, we decided to work on another part of our culture which appears in our mind as a good representative of gender stereotypes: movies. In fact, while doing some research on the movie industry in order to decide with which angle we would like to approach our dataset, we came across this sentence: 

“If [Marilyn Monroe] still fascinates us so much, it is because her story echoes the diktat that continues to mark out women's lives in a world controlled by the male gaze.” 

This powerful observation signes the introduction of the documentary “Becoming Marilyn”, released in 2021 by Arte Cinema. And it taught us two things: that women characters have failed to be more than projections of men’s expectations, and that the cinema in itself can be consider as a representation of our society and its diktats.

With this project, we would like to tackle the subject of gender representation in movies across time. Strong believers that women are more than gentle creatures and men are not only super strong, we want to investigate if the movies industry followed and still follows these stereotypes, and how does it varies between countries and movies genres.

### W**hat is the gender parity across movie genres?**

We decided to start our investigation with an increasingly used metric these days: gender parity.  Calculated as the ratio of women among the actors displayed in each movie, we wanted to see if this metric is impacted by the movie genre. 

Displayed below, the gender parity by movie genres with 95% confidence interval calculated for each genre that appears more than a 100 times in our dataset, and the evolution of this ratio before and after 2000. Only red arrows show evolution statistically significant under α = 0.05. 

*graph*

The first main result of this study is that sadly, there is no movie genre that has a gender parity over 50%, even within the 95% confidence interval. Secondly, among the ten highest ranked genres, five of them are a type of *comedy*, and three of them contain the world *romance* or *romantic*. Women are therefore more displayed in movies created for a mainstream audience, and are more represented in movies that include a romantic plot (which does not seem too surprising, since most of the relationships displayed in movies are heterosexual). On the other hand, the five lowest ranked genres include *War*, *Gangster*, *Western*, which are known to display a high level of violence and the use of weapons. 

We can also conclude that movie genre is significantly impacting gender ratio, since the average ratio is out of confident intervals for many movies genres.

To bring some good news, the evolution of gender parity across movie genres shown that for most of them, this evolution is positive. The winner of this race is by far the *Japanese movies* genre, with an increase of approximatively 15%. Its evolution is displayed below, and one can see the good overall improvement, even if it’s not a linear one. Among the ten highest ranked genres, two of them (*Romantic Comedy* and *Romantic Drama*) show a statically significant improvement, and among the ten lowest ranked, two of them also show a positive evolution (*Action* and *Action/Adventure*). Therefore, the conclusion of this evolution is that the best ones often do better over time, and the others also try to do better in general, which is full of hope for the future!
### W****hat is the evolution of gender parity in films among countries over time?****

After considering movie genres, the next thing we wanted to tackle was the evolution of this gender parity among countries. Again, we looked at this value with 95% interval, here among the countries that had more than 20 occurrences. We also considered the evolution of this ratio before and after 2000. Only red arrows show evolution statistically significant under α = 0.05. 

*graph*

Little glimpse of patriotism here for the French members of the team: France comes out first, followed by Canada. Are countries containing French speakers less sexists than the rest? The answer could be yes considering the gender ratio in their movies. 

Let’s give a look at the rest of the facts. Sadly here, once again, the gender parity does not reach the 50%, even within the 95% confidence interval. Beside, we cannot observe a significant impact of country on the gender ratio. Indeed, average ratio is inside of confident intervals for many countries. We can also say that this ratio does not seems to depend on the continent in which the countries is located. For instance, France and Czech Republic are respectively ranked 1st and 23rd, and South Korea and Hong Kong are 6th and 18th. To support this idea, we decided to plot these data on a heatmap, displayed below. 

Among the 24 countries displayed in these graphs, only three of them show a significantly positive evolution between before and after 2000: USA, Japan (which is coherent with the evolution of the “Japanese movies” genre studied above) and South Korea.

![image](assets/world_heatmap_2022.png)

Therefore, we are a bit disappointed by the conclusions of these analyses since most countries do not show a significant evolution. Feminists and societies still have a lot to do in each of them …


### C. Is there a variation in the box office revenue depending on the gender parity? Has it change over the years?

### D. Is there a variation of the main attributes -agent verbs, patient verbs and attributes- given to each gender across time?

### E. Do the mean age of the actors, male and female, evolves over the years? (with the cliché in mind that +40-year-old actresses are "outdated")

