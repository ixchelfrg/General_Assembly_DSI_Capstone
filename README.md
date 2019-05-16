
<h1 style="text-align: center;">Capstone: Recommender System for Reddit Posts</h1>

***

## Problem Statement

The goal of this project is to build a recommender system that will take in a description of what a user would like to quantify, in a sentence or paragraph format, and output five URLs of the most similar subreddit `r/QuantifiedSelf` posts. This will allow the user to access what other people are discussing, relevant to users' specific interest.

***

## Executive Summary

For someone to take control of different aspects of their life, they need the knowledge to do so. There is an increasing trend of those looking to accomplish this task by collecting personal data, on their health, sleep, finances, and more. However, for someone new to this movement, it can be overwhelming to look for the right tools that will facilitate the collection of this data. 

In 2007, Gary Wolf and Kelly Kelly started a website called [The Quantified Self](https://quantifiedself.com/), that would facilitate support of these personal projects by leveraging the power of community. 

> The Quantified Self is an international community of users and makers of self-tracking tools who share an interest in “self-knowledge through numbers.” If you are tracking for any reason — to answer a health question, achieve a goal, explore an idea, or simply because you are curious — you can find help and support here. [What is Quantified Self?](https://quantifiedself.com/about/what-is-quantified-self/)

The group started with a meetup of 30 curious attendees, however now it has grown to a community of [more than 20,000 members in 188 cities](https://www.forbes.com/sites/stevenrosenbaum/2015/05/17/the-quantified-self-measuring-to-curate-your-life/#6c93b2945ab5). In 2012 the [Quantified Self Institute](http://qsinstitute.com/about/what-is-quantified-self/) was established at the Hanze University of Applied Science in the Netherlands. The Quantified Self community connects via The Quantified Self website, meetups, and now with the increasing use of social media, sites like Reddit are also ways to discuss self-tracking tools and methods. Reddit's subreddit [r/QuantifiedSelf](https://www.reddit.com/r/QuantifiedSelf/) currently has 5,300 members.  

A newcomer that searches on Amazon for a fitness device or a mood app in android's or Apple's app stores will quickly encounter that there is a confusing supply of tools. Which do they pick? 

This project assists those interested in starting a personal data project, as well as those that would like to read up on what other's in the community are doing or discussing. The recommender system asks the user to describe what they are interested in knowing more about and outputs five URLs that direct to similar subreddit posts.

[![The Quantified Self YouTube Video from New Scientist](https://img.youtube.com/vi/8wqC6ad1V_Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=8wqC6ad1V_Q)

<br>Further Information of Movement and Other Related Resources:<br>
[New York Time's Article: The Data-Driven Life](https://www.nytimes.com/2010/05/02/magazine/02self-measurement-t.html)<br>
[Gary Wolf at TED Talk in Cannes](https://www.ted.com/talks/gary_wolf_the_quantified_self/transcript?language=en)<br>
[Quantified Self Blog](https://quantifiedself.com/blog/)<br>
[Quantified Self Get Started Guide](https://quantifiedself.com/get-started/)<br>
[Quantified Self Forum](https://forum.quantifiedself.com/c/quantified-self/apps-tools)<br>

***

## Data

1,403 posts were collected from Reddit's subreddit `QuantifiedSelf` with corresponding 3,483 comments, through the [Praw](https://praw.readthedocs.io/en/latest/) library and [Pushift.io](https://pushshift.io/), combined by Pepper Johnson's code found in [GitHub](https://github.com/pepper-johnson/sack_lunch/blob/master/Notebooks/Bots/Reddit.ipynb) and explained in [How to Scrap Reddit using pushshift.io via Python](https://medium.com/@pasdan/how-to-scrap-reddit-using-pushshift-io-via-python-a3ebcc9b83f4). Posts were created from Sunday, May 29, 2011 to Wednesday, May 15, 2019. Text data was combined from the post's titles, comments, and available self text. Praw's documentation has a description of the data features, on the pages [Submission](https://praw.readthedocs.io/en/latest/code_overview/models/submission.html) and [Comment](https://praw.readthedocs.io/en/latest/code_overview/models/comment.html) sections.

### Notebooks
[01-Data Collection]()<br>
[02-Exploratory Data Analysis]()

***

## Model

***

## Findings

***

## Next Steps


```python

```
