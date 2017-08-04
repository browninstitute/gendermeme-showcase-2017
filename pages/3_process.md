---
layout: page
title: Process
published: true
---
With this background in mind, we decided to build the GenderMeme tool, which takes the text of an article as input, and produces as output the list of people mentioned in the article, their genders, and what each person was quoted saying. We can run this tool on large sets of news articles, and analyze the results to glean insights into gender representation in the media.

Building the tool was the most challenging part of our project, since we had to wrestle with some of the complexities and ambiguities of natural language. After building a first version of the tool, we manually annotated a set of news articles and compared our tool’s output to the manual annotations. This allowed us to understand where our tool was making errors, and what its overall accuracy was. This way of identifying the sources of error allowed us to follow an iterative process of improving the code to stop making common errors, and gradually got us to our current accuracy rates.