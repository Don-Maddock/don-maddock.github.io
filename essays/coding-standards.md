---
layout: essay
type: essay
title: The Inspector Gadget
date: 2020-02-13
labels:
  - Coding Standards
  - Learning
---

ESLint is the helping hand that guides you. Other times it's the hand that slaps you on the wrist for forgetting a space key. While following coding standards can feel like adding to the stack of problems to worry about, I believe that their presence is a great asset to both experts and novices alike.

Setting up ESLint was a task in itself. I had to dive into an IDE I've never used, to change settings I've never heard of, and include files I've never seen, all to impose some rules onto myself. After almost an hour of troubleshooting, I was finally ready to code. It helped. The benefits of the feature proved to be visibly helpful and yet also somewhat subtle.

Cleaner code is the obvious benefit. Sure, it can be annoying to be thrown an error every line. A space after every parenthesis, one too many new lines, the classic missed semicolon. ESLint would alert me about problems I didn't even think were problems. It was a pain, but like a cat sprayed one too many times with water, you begin to not repeat them. Suddenly, your code is beginning to like a lot nicer. When other people look at it, they can more clearly see the information they need to see. If they have also been following these same standards, they'll feel even more at home editing what visually looks like their own code. Easier reviewing for your peers, and even your future self, is one of the best ways to improve code quality.

Inspections are also very helpful in more ways than what's immediately obvious. For example, auto completing variable and function names is very useful. One more thing to let your IDE do for you could be one less hour you have to spend looking for a typo you accidentally made 50 lines back. Sometimes typing out longer variable names over and over can be a chore. Type them enough and it's tempting to name them something short, but not always concise. In most situations, I can much more quickly understand "temperatureInCelcius" over "tempC", or "gradeTotal" over "sum".

The inspector will also ask the questions I might be too focused, or maybe tunnel visioned, to see. When will this loop exit? Why haven't you used this variable yet? What types of data go into these functions? Those questions that ESLint asks are the fixes that can really help avoid future problems.

In the end, coding standards are the rules I voluntarily choose to follow. Everyone jaywalks now and then, but you understand why you want to wait at crosswalks. Just like there, you know that by following these coding standards, they'll ultimately help you become a better coder. 

Or you can use the "Reformat Code" command and have IntelliJ fix everything for you. No one will ever know.


