---
title: Today I Read Cohen (1994)
layout: post 
---

Today I read a paper called The Earth Is Round (p<0.05) by Jacob Cohen, which was published in American Psychologist in 1994. I had a difficult time finding a link to a downloadable version of the file that wasn't paywalled, but you can get a citation for it at [this](https://scholar.google.com/scholar?q=the+earth+is+round+jacob+cohen&btnG=&hl=en&as_sdt=0%2C22) link.

<!--more-->

# Intro

There is a battle being fought in the social/behavioral sciences about whether significance testing is really the best approach for deciding when a research finding is "meaningful" or "substantial" (i.e., not just a fluke). While arguments on both sides of this point have been leveled since Ronald Fisher first popularized the concept of the _p_-value in the early 20th Century, things have heated up recently. Mostly, this was the result of the failure of [this](https://osf.io/ezcuj/) project to reproduce significant findings for large numbers of studies across a huge range of disciplines within Psychology. Whether or not these results want to make you throw up your hands and throw in the towel, the state of the art for Psychologists obviously needs to change, and soon. So the next few papers I've selected are all mostly concerned with this issue.

# Summary

"The Earth is Round (p<0.05)" is a kind of think-piece or historical review of the status of "null-hypothesis significance testing (NHST)" -- effectively, of the whole concept and status of tests based around _p_-values. Although the language is a little bit overblown as a result (Cohen describes himself in it as a "grouse"), this paper provides the simplest description of the core flaw with the NHST approach:

> What's wrong with NHST? Well, among many other things...what we want to know is "given these data, what is the probability that H<sup>0</sup> is true?" But as most of us know, what it tells us is "Given that H<sup>0</sup> is true, whati s the probability of these (or more extreme) data?"

He continues to point out the apparent difficulty researchers also have in remembering:

	1). that the alpha value (the criterion value that describes the maximum acceptable possibility of comitting a type one error) does _not_ describe the probability that the null hypothesis is _correct_.

	2). that conditional probabilities are not transitive (i.e., the probability of the null hypothesis being true given the data is not the same as the probability of the occurence of the _data given the null hypothesis_).

	3). that the null in "null hypothesis" does not necessarily refer to a state of affairs concerning a population parameter that is thought to take a value of _zero_ (and that even if it did, the probability of such a parameter having an exact integer value in that way is also effectively zero).

	4). that as a correlary of point 3, the real risk is committing a type II error (failing to reject the null hypothesis in the presence of a real effect), not a type I (rejecting the null hypothesis in the absence of an effect).

Ultimately, his proposed response is that we first do not seek out a purely mechanical or procedural alternative to NHST. He also suggests that we rely more heavily on exploratory data analysis, particularly in conjuction with graphics and with reports not just on differences but on _magnitudes_ of differences (i.e. confidence limits).

# Critique

Again, if you can get through the dense, sometimes flowery language, then this paper is a compelling and thoughtful summary of the core issues with the bedrock method used by almost all Psychologists today. That such a respected statistician would suggest that behavioral scientists should lean more heavily on graphical methods than they currently do should make this point be taken more seriously than it currently seems to be. His complaints about the lack of reported effect sizes, however, land less for me -- even most graduate students I know now do this routinely.