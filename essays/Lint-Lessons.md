---
layout: essay
type: essay
title: Lint Lessons
published: false
# All dates must be YYYY-MM-DD format!
date: 2022-02-10
labels:
  - Javascript
  - Coding Standards
---
## Wax on, wax off
There are times where ESLint can feel like my mom nagging me to do dishes. As soon as I declare a variable, I'm already being pestered that it's not being used. The code still runs right? Surely these double quote marks can't be *that* big of a deal. But from each error thrown at me, I learn a bit more Javascript. For example, let and const have been a new concept I have yet to really put any thought into. However, when I get an error from Lint saying that there's no reason to use let if I never reassign a variable, I start to really consider the different use cases between the two. I've gone from never using const to actually thinking about when I'll need it because of ESLint.

This frustration of constant errors is what makes lint so effective as a learning tool. Checking the AirBnB style guide, within the first two sentences I learned something I didn't know about Javascript. I probably would have never looked through this page normally, but I did simply to be more familiar with what might throw me an error. I find myself trying to proactively avoid those pesky red marks from appearing in the first place.

Before I knew it, I've unconsciously writing better code. The benefits of this seem worth the headache. Code that's easier to read is easier to debug, and when your code looks the same as other people using the standards, it's a lot easier to wrap your head around, and a lot less embarrassing when people are evaluating your work. When it's time to evaluate your own work, it'll be a lot easier to read and make sense of.

## Confession Time
I have yet to do any major code refactoring for code I've written (maybe not the best line to put in a resume essay). The scope of my class and personal projects have simply never been large enough to warrant it. That being said, I can understand the merits of it. Like cleaning a messy room, work is much more smooth without a growing mess.

This is extra important when the code is something you haven't touched in months, or never touched at all, in the case of somebody else's code. Coding standards can save a lot of refactoring time when your initial code is already extra clean. Of course, you'd still be changing things like variable names of how code interacts with each other, but at least then you're focusing on that rather than the less important things that ESLint already caught for you.
