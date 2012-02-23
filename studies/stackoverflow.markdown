---
title: Questions and Answers
layout: default
---

On the site [stackoverflow](http://stackoverflow.com), programmers can post a question, other programmers can answer those questions, and both questions and answers can be voted on. Stackoverlow is very popular with programmers (earlier this year they were at [95 million page views per month](http://highscalability.com/blog/2011/3/3/stack-overflow-architecture-update-now-at-95-million-page-vi.html)) and represents an interesting dataset for software engineering researchers. Here is a [summary of the number of questions that have been asked, etc](http://data.stackexchange.com/). The goal of this study is to use data from stackoverflow to develop theory about how stackoverflow works and more generally about the process of _social learning_ .

Background reading (only loosely relevant):

* Eisenhardt, Kathleen M. Building theories from case study research. Academy of Management Review, 14:4, pp. 532-550, 1989.

## Data collection

Develop a reasonable strategy for selecting a subset of the questions (and associated answers) on stackoverlow. Your strategy should ensure that your analysis can focus on questions that have multiple answers, including some "highly" rated answers. Based on your strategy build a [search query](http://stackoverflow.com/search) that will get you all posts matching that query. In all likelihood this search will return hundreds or thousands of results, but since this is a "mini" study your analysis should focus on only the first 20 posts returned. Archive or (at least) bookmark these posts and note the time and date you performed the query.

## Analysis

Your analysis will be based on comparison (e.g., compare answers within and between questions) along various dimensions or based on properties. The simplest dimensions/properties can be based on easily collected information such as the number of votes, the time between the question being asked and the answer being given. Other dimensions/properties you will have to develop on your own, by considering what _kinds_ of questions are there (how-to's, debugging, ...), what _kinds_ of answers are there (tutorials, comparisons of approaches, ...), and other things you think are important. Once you have the dimensions defined (likely you will do this iteratively) I suggest you put each of the questions and answers in a spreadsheet, with the columns representing the dimensions.


    Question  Answer   Votes  Delay   Answer category        ...
    ------------------------------------------------------------
    9421091   Ouah     3      5mins   tutorial               ...
    9421091   Brian    0      15mins  code with explanation  ...
    ...

Such a spreadsheet will allow you to compare along dimensions to build toward theory based on the relationships between these properties. Consider the following guiding questions (or others you can come up with) in your analysis.

* What properties of question and answers influence the rating of those?

* What makes for a "good" answer? Is this dependent on the kind of question being asked?

* What is the nature of the learning and teaching process?

## Report

Prepare a *one page* report about your study. Your report should have the following three sections.

* _Study description_. Describe selection criteria and associated search. Mention any setup issues that arose (things that could be improved).

* _Highlight some of the results_. Summarize your results and include a list of the dimensions and relationships you discovered. Most importantly, highlight some of what you found interesting. 

* _Limitations and applicability_. Reflect on the problems with this study and report on when this type of study would be applicable and when it would not be. Don't worry about limitations that are particular to our "mini" version of this study (e.g., only 20 questions) instead focus your comments more broadly on this type of experiment.

Your report is due in class. Please be prepared to discuss your study in class.

## Notes

I encourage you to work with a partner for this study as getting someone else's perspective will be useful.

Be bold in developing your theory. Top marks will go to those with something interesting to say at the end of the study. Of course, what you say needs to be grounded in the data.
