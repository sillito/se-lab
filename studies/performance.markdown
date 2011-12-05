# Writing high performance code

An iterative approach to writing a piece of software

## Setup

Recruit 2 programmers with experience programming in Java to participate in this experiment. In the following I'll call them participants X and Y and you should randomly assign which participant is X and which is Y. Each participant will take part in one 60 minute session. Sessions begin with 5 minutes of instruction (to explain the task and study setup) followed by 55 minutes working on the task.

* Session 1: Iteration (Participant X)

  The participant will first spend 40 minutes developing 3 completely different approaches (i.e., programs) to this task. Some structure should be provided to encourage participants to spend about 12 minutes on each program. The participant will test all three programs using the provided testing tool (see below). Based on the 3 programs and the feedback from the tool, the participant will spend the final 12 minutes or so implementing one more approach (i.e., a final program).

* Session 2: Parallel (Participant Y)

  The participant will spend approximately 12 minutes developing an approach to the task (i.e., they create one program). Then they test the results using the provided testing tool (see below). They then produce a new program (likely by modifying the first program) and run the testing tool again. This continues until they time is up. Ideally, the participant will create a total of 4 versions of their program.

*Assigned Task:* Participants will be assigned to produce an efficient (with regards to running time and memory usage) program that solves the following problem...

*Testing tool:* In preparation for the session, prepare a simple tool the participants can use to test their program. Make sure the tool has a range of cases that will exhibit different performance characteristics. The output from this tool should look something like the following:

	Max memory usage: 5678KB
	Mean running time: 2m 3s 234ms
		<break down of cases and running times>
	Faults:
		<List of input/output values that the code fails on>

## Analysis

Quan: compare performance of final program from each session. Use means, but also compare cases to get deeper insights.

Qual: Take notes during each session -- where are their ideas coming from? how is previous work built on?

## Report

Prepare a *one page* report about your study. Your report should have the following three sections.

* _Study description_. Describe your participants and particulars of your study setup over and above what I have described above. Mention any setup issues that arose (things that could be improved).

* _Highlight some of the results_. You are not expected to report on a detailed analysis of your results, but please highlight some of what you found interesting. Include a brief table summarizing the quantitative results.

* _Limitations and applicability_. Reflect on the problems with this study and report on when this type of study would be applicable and when it would not be. Don't worry about limitations that are particular to our "mini" version of this study (e.g., only 2 participants) instead focus your comments more broadly on this type of experiment.

Your report is due in class. Please be prepared to discuss your study in class.


## Notes

Make sure none of the participants participate in studies by more than one of the students in this course.

As usual, you should feel free to adjust this study as needed. For example, you may want to adjust the tasks and programming language depending on background of your participants. Similarly, if you are less interested in performance and more interested in (for example) design, feel free to restructure the assignment to focus on which approach leads to "better" design.

Like all of the studies used in this course you are allowed to work alone or you can team up with another student and submit one report as a team. However, please do not work with the same partner more that a couple times over the term.

As a last resort, you can use other students in the class as participants in the study, but please do try hard to find other participants first before asking a fellow student.

You are responsible for arranging rooms and equipment. **Plan a head**.
