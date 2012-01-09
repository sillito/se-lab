---
title: Comparing pair programming to code review
layout: default
---

A _defect_ (or fault) is an imperfection in source code (or other artifact). It is the result of an error made by a programmer (or other stakeholder) and can result in a failure in the executing system, assuming the right conditions occur at runtime. For example, in the following code there is a defect in the stopping condition of the loop. In some conditions (i.e., when the `break` statement is never hit) this will result in a failure (an exception from accessing an out of range element in the array).

	for (int i=0; i <= array.length; i++) {
	    if (array[i] == target)
	      break;
	}

Two software engineering techniques that aim to reduce defects are _pair programming_ (two programmers working together on the same task at the same workstation) and _peer review_ or _code review_ (code written by one developer is reviewed by another developer). The main goal of this study is to see which of these techniques is more effective at reducing defects. In this part of the study we will be concerned only with _data collection_, saving data analysis for later.

Here is a sample [informed consent form](pair-programming-consent.html). Copy and edit this sample as appropriate. Your final version should have the University of Calgary's logo at the top.

## Background Reading

Williams, Kessler, Cunningham and Jeffries. _Strengthening the case for pair programming_. IEEE Software, Aug 2000, 17(4), pages 19-45.

## Setup

Recruit 2 programmers with experience programming in Java to participate in this experiment. In the following I'll call them participants X and Y and you should randomly assign which participant is X and which is Y. Each participant will take part in two 30 minute sessions. Sessions begin with 5 minutes of instruction (to explain the task and study setup) followed by 25 minutes working on the task. All sessions will be recorded using screen capture software.

* Session 1: Participants X and Y pair programming

  Both participants work together on the assigned task using one workstation. Participant X is to have control of the keyboard and mouse.

* Session 2a: Participant X solo programming

  Participant X works by him/herself on the assigned task, 'talking-aloud' as they do so.

* Session 2b: Participant Y reviewing X's code

  Participant Y is given Xs implementation from session 2a and asked to review the code (identify defects) with out making any changes to the code and 'talking-aloud' as they do so.

*Task A* In Java implement a [Trie datastructure](http://en.wikipedia.org/wiki/Trie). Only Java Standard libraries should be used. The following methods should be implemented:

	class Trie
	    boolean isEmpty()
	    void put(String)
	    boolean find(String)

*Task B* In Java implement a [binary search tree](http://en.wikipedia.org/wiki/Binary_search_tree). Only Java Standard libraries should be used. The following methods should be implemented:

	class BinaryTree
		boolean isEmpty()
		void put(Comparable)
		boolean find(Comparable)

You should randomly decide the order of the sessions above and randomly assign task A and task B to sessions. Participants in sessions 2 and 3 (i.e., when they don't have a partner) should be asked to 'think-aloud' during the session. For all sessions, the researcher should be present and take field notes about interesting events, comments, etc.

## Report

Prepare a *one page* report about your study. Your report should have the following three sections.

* _Study description_. Describe your participants and particulars of your study setup over and above what I have described above. Mention any setup issues that arose (things that could be improved).

* _Highlight some of the results_. You are not expected to report on a detailed analysis of your results (we'll do more analysis of this data later), but please highlight some of what you found interesting.

* _Limitations and applicability_. Reflect on the problems with this study and report on when this type of study would be applicable and when it would not be. Don't worry about limitations that are particular to our "mini" version of this study (e.g., only 2 participants) instead focus your comments more broadly on this type of experiment.

Your report is due in class. Please be prepared to discuss your study in class.

## Notes

Make sure none of the participants participate in studies by more than one of the students in this course.

As usual, you should feel free to adjust this study as needed. For example, you may want to adjust the tasks and programming language depending on the background of your participants.

Like all of the studies used in this course you are allowed to work alone or you can team up with another student and submit one report as a team. However, please do not work with the same partner more that a couple times over the term.

As a last resort, you can use other students in the class as participants in the study, but please do try hard to find other participants first before asking a fellow student.

You are responsible for arranging rooms and equipment. **Plan a head** and ask for support if needed.
