---
title: Mining Software Repositories
layout: default
---

_Mining software repositories_ is a branch of software engineering research that focuses on analyzing data available in software repositories (e.g., version control systems or issue tracking systems) to uncover insights about software systems and projects. There is even a [mining software repositories conference](http://2012.msrconf.org/) now. The goal of this mini-study will be to explore development of the linux project using version control system data.

Background reading:

* [How to Participate in the Linux Community](http://www.linuxfoundation.org/sites/main/files/How-Participate-Linux-Community_0.pdf) by Jonathan Corbet.

## Setup

Jonathan Corbet describes the linux project as follows:

> The Linux kernel, at over 6 million lines of code and well over 1000 active contributors, is one of the largest and most active free software projects in existence. Since its humble beginning in 1991, this kernel has evolved into a best-of-breed operating system component which runs on pocket-sized digital music players, desktop PCs, the largest supercomputers in existence, and all types of systems in between. It is a robust, efficient, and scalable solution for almost any situation.

By almost any measure Linux is one of the most successful software engineering projects of all times, making it (arguably) a worthwhile topic of study. Many of the practices and tools used by the project are somewhat unique and perhaps interesting for project managers (etc) working on other projects. 

To get started, download the Linux mainline repository (maintained by Linus Torvalds) and the linux-next staging repository and maintenance branches. Feel free to analyze other trees as well, such as the stable trees. Linux-next roughly represents the future of the mainline, except that linux-next is more volatile.

    git clone git://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git
    git clone git://git.kernel.org/pub/scm/linux/kernel/git/next/linux-next.git

Create a script to collect data from those repositories to explore aspects of the Linux development project. Here are some topics/type of data to consider exploring (but you do **not** need to look at all of these). 

- What is the flow of patches between the two repositories? (E.g., How long is a patch in linux-next before being merged into the mainline). Can you develop some estimates about how long it takes code from the time it is ready, until it is "released"?

- How likely is that a patch gets reverted after being committed to either tree. Is there a temporal pattern to this?

- Quantify the number of patches incorporated overtime across all branches. Look at patterns within and between the two trees. Are there patterns that point to important aspects of the project?

- Each commit has an associated _author_, sometimes accompanied by a commit message listing other people involved in the patch (e.g., who reported it and who signed off on it) as shown below. Are there patterns that are important regarding who is involved in what roles overtime?

        commit 847854f5988a04fe7e02d2fdd4fa0df9f96360fe
        Author: Tejun Heo <tj@kernel.org>
        Date:   Wed Feb 29 05:56:21 2012 +0900
            
            memblock: Fix size aligning of memblock_alloc_base_nid()
            
            Reported-by: Meelis Roos <mroos@linux.ee>
            Signed-off-by: Tejun Heo <tj@kernel.org>
            Cc: Linus Torvalds <torvalds@linux-foundation.org>
            Cc: Andrew Morton <akpm@linux-foundation.org>
            Signed-off-by: Ingo Molnar <mingo@elte.hu>
            LKML-Reference: <alpine.SOC.1.00.1202130942030.1488@math.ut.ee>

- Others?

## Report

Prepare a *one page* report about your study. Your report should have the following three sections.

* _Study description_. Briefly describe your data collection and analysis.

* _Highlight some of the results_. Provide some highlights of the results that you found interesting. Since we are just considering VCS data, you are getting only a partial view of the data, so you may not always know the _why_ of the patterns you find.

* _Limitations and applicability_. Reflect on the problems with this study and report on when this type of study would be applicable and when it would not be. Don't worry about limitations that are particular to our "mini" version of this study instead focus your comments more broadly on this type of experiment.

Your report is due in class. Please be prepared to discuss your study in class.

## Notes

* It will likely be best to work on this study with one or two partners, so the programming work can be shared. Just submit one report for each team.

* For each of these questions, the answer may not be simply one number -- you may need to consider the mean, the minimum, the maximum and the standard deviation. 

* You may also want to create graphs of the values to explore distributions and relationships.
