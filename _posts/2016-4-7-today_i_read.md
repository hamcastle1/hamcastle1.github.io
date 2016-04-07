---
title: Today I Read Tseng et al (2013)
layout: post
---

Today I read "High-throughput classification of clinical populations from natural viewing eye movements" by Tseng et al. It was published in the Journal of Neurology in 2013. A PDF version should be available [here](http://link.springer.com/article/10.1007/s00415-012-6631-2) -- I didn't check carefully to see whether the PDF is available only by dint of being within NEU's network. 

<!--more-->

# Intro

Today's paper is kind of a cheat -- I've read it before, and many times to boot -- but it's important to me for a lot of reasons. Finding this paper effectively by accident confirmed my long-standing belief that eye movement data could be used to exactly this: parse out clinical populations from neurotypicals. This discovery was more or less responsible for me ending up in grad school at all. 

As Itti is giving a talk here today, and one at least partially concerned with this material, I thought it would be appropriate to review it here.

# Summary

In this paper, the authors attempted to use eye movement data to classify and separate three groups of subjects: those with ADHD, those with fetal alcohol syndrome, and neurotypicals. Subjects in all three groups watched frame-shuffled movies of natural scenes and had their eye movements recorded during the process. Support vector machines (a kind of machine learning technique that can draw a line that best separates groups of data across very high dimensional spaces) were fitted to the data. These planes were then used to classify data from each subject as belonging to a particular subject group. Both neurological populations' data could be reliably and accurately separated from the neurotypical population, though classification performance between them was not as successful.

# Critique

Obviously, a cool and potentially valuable use of what I see as the highest-volume source of data most behavioral scientists will ever get (outside e-phys & imaging stuff). My only criticism is that the type of algorithm used -- the support vector machine -- is what is called a "black box" algorithm in that it is not constructed on the basis of a theory (it just does optimization against a set of purely mathematical constraints). This means that this result doesn't tell us anything meaningfully different about _why_ these groups have different patterns of eye movements, just that they _are_ different in a mathematically robust way. While this is great for doing fast, efficient classification in the way that say, a clinician might, it does very little otherwise to advance science.