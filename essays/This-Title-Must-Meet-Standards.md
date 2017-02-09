---
layout: essay
type: essay
title: This Title Must Meet Standards
date: 2017-02-08
labels:
  - Software Engineering
  - Learning
---

<img class="ui medium left floated image" src="../images/codequality.png">

## Why Are They Necessary?

Standards are important for quality regardless of the affiliated industry or profession. For software engineering, this goes beyond the consumer experience and into the standards of workflow. By workflow, I’m referring to the methods a software engineering team implements as a means of developing code, organizing files, setting up deadlines etc. For this writeup, I’ll specifically focus on the importance on having coding standards for software engineering and the underrated benefit behind its use for learning/educational purposes.

## i++ vs. i+=1

It’s been almost a week since I started learning how to use [IntelliJ](https://www.jetbrains.com/idea/) as an IDE for developing JavaScript in my software engineering class. My professor, Philip Johnson, instructed us to use [ESLint](http://eslint.org/) (a type of coding standard) with IntelliJ when going through the process of learning how to use it. From the first couple of days using ESLint, I was really annoyed with the amount of syntax errors it produces while I’m coding. One error that ESLint flagged was the use of i++ instead of i+=1 inside a for loop. The [ESLint documentation](http://eslint.org/docs/2.0.0/rules/no-plusplus) argues that the use of unary operators (i.e. ++, --) reduces code clarity and can lead to semantic error, but I still disagree with this rule because 99% of the time a programmer would use i++ in the for loop instead of i+=1. The use of i+=1 is too “extra” and its unconventional use could cause people to be more confused.

After using IntelliJ with ESLint for a few more days, I began to get accustomed to the IDE and the set coding standards. I realized that the coding standards helped ease the pain in learning an IDE and could benefit teams. Like I said earlier, coding standards can increase workflow. If a team didn’t have a coding standard and everyone decided to use different coding styles, the team will end up wasting time trying to constantly transition to reading different code styles from teammates. However, if a team followed the same standards, they won’t need to waste any time trying to read someone else’s code because everyone is following the same standard, so the code is organized in the same way. By improving readability, organization will improve and thus, productivity will increase.

## Coding Standards in Education

Despite the “picky” nuances of coding standards, I’m still an advocate for having a coding standard in the software engineering and especially in the learning environment. I firmly believe that there should be more strict standards at lower level classes in general for any major-related course (excluding general education requirements) because students who are starting with the fundamentals need the most guidance to give them a sense of direction. Standards provide a set of rules backed by reasoning that’ll assist students in avoiding unforeseen mistakes and teach them how to develop quality code. 
