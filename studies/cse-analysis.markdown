---
title: Analyzing CS&E Interviews
layout: default
---

In this study you will be analyzing data collected from a previous study [exploring software engineering issues in a CS&E content](cse.html). Making sense of purely qualitative data is challenging, and how you do it can vary significantly between studies. What I have described below (in the Setup section) is a generic description of a typical approach to this analysis.

## Background Reading

* Andrew J. Ko, Robert Deline and Gina Venolia. _Information Needs in Collocated Software Development Teams_. International Conference on Software Engineering, 2007.

## Setup

To do this analysis you will need transcripts from two interviews, so please share transcripts with each other. In general, your analysis might involve three main activities as described here, however, given the small amount of data you will be dealing with, and the time constraints, feel free to **focus on just the first two activities**.

1. _Open coding_. Coding is about mapping concepts to data. In the case of open coding it is also about identifying concepts. Open coding may take more time (e.g., may require recoding) and may result in unused coding. In this stage of the analysis you are to go through the data (sentence by sentence and paragraph by paragraph) naming the concepts you find. You can do this on paper (by writing in the margin), or using a tool like the comment feature in MS Word. The following is some sample interview data and some coding:

	> Well that may be one application for us, but if we change the way locking happens on an insert, that affects a hundred different transactions each of which may process 45,000 transactions a day (or more). If we make one little oops, then it affects a lot more than just a bit of our code.
	
	> **Coding:** _application is part of a large process, dependences and consequences measured in transactions/day_
	
	> If they [SAP people] change their code then all these documentation have to be reviewed over again and we have to meet again and it has to be a formal... We have to sit there and go through the process again. What change you are actually making, is this going to affect anything else?
	
	> **Coding:** _reverse dependences, dependencies are explored in meeting_
	
	> When we change a core component it usually takes a long time, even for small changes. And for the most part we just don't change them.
	
	> **Coding:** _changes to core vs. noncore components, procedural friction to change, long time vs. small change, reluctance to make changes_

2. _Theme selection_. Once you've identified the important concepts in the data, next need to "select" the concepts that are the main themes (or categories) and begin to think about relationships between themes. Some codes may be "promoted" to themes at other times, the themes may abstract over several codes. Other codes may map to dimensions of a theme or conditions under which theme applies. Some people create affinity diagrams to help with this process.

	<a href="http://www.flickr.com/photos/logicalrealist/324421037/" title="looking more colorful by Sean Munson, on Flickr"><img src="http://farm1.staticflickr.com/144/324421037_47fdfab2d2.jpg" width="500" height="375" alt="looking more colorful"></a>

3. _Focused coding_. The themes you have identified, and the relationships between those themes form the skeleton of a theory. In this analytic stage of the research you would elaborate the themes, think through the relationships between themes, examine processes, conditions under which things occur, implications of the relationships you identify, consequences, draw pictures for exploration relationships, try to fit what you have found with existing theories, revisit the data to get more detail, look for patterns, etc.

## Report

Prepare a *one page* report about your study. Your report should have the following three sections.

* _Study description_. Describe your approach to analyzing your data. Focus on what you did over and above what I have described above setup.

* _Highlight some of the results_. Highlight the themes you have selected along with some of the underlying codes. You may want to show some amount of data in your report (space permitting). Think hard about what is interesting in your analytic results.

* _Limitations and applicability_. Reflect on the problems with this type of study and this type of analysis, report on when this type of study would be applicable and when it would not be. Don't worry about limitations that are particular to our "mini" version of this study (e.g., only 1 participant) instead focus your comments more broadly on this type of study.

Your report is due in class. Please be prepared to discuss your study in class.
