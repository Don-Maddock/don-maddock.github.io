---
layout: essay
type: essay
title: Find and Replay
# All dates must be YYYY-MM-DD format!
date: 2020-04-30
labels:
  - Design Patterns
---

## Find the Design
To me, design patterns are a two part process. The first is identifying your problem. In many branches of math or science, one good way of dealing with something you don't know is to transform it into a problem you know a lot about. This has been one of the key take away points to my Algorithms class, and it's refreshing to see it be applied to actual coding. Just like how chemists already know how undiscovered elements would behave by where they'd fall on the periodic table, or a biologist could list the characteristics of a new species from which family they belong to, knowing what kind of beast your new coding problem is similar to will greatly help solve it. After that comes step two. Design patterns are your toolbox to solve them, and now that you know the problem, you can grab the right tool to solve it! There's no need to remake these tools yourself. After all, you have years of designer work behind the creation of that tool. It is up to you, however, to have a wide range of tools to work with. Having just a hammer won't do much against a screw, and a screwdriver is useless if you don't know how to use it. By learning and practicing design patterns, you can be more confident that you'll have the tools to deal with any coding problem that comes your way.
## Orderly Pattern
In my own experience, the biggest boon of design patterns is when scope starts to get way over your head. With small projects, you can certainly just throw together some code that works. But, as projects get bigger it becomes a lot harder to deal with. Going out of your way to use a pattern can keep things organized. One of my favorite patterns is the State Machine. The pattern aims to change an object's behavior based on the state it's in. Game design is one of my hobbies, and it greatly helps organize your main character code in particular. Say you want the character to run when you press B. It's easy enough to do, check each frame if the player is pressing b and execute your code. But maybe they're on a ladder and you want B to dismont. Or have B drop something they're holding. Or maybe to swim if they're in water. It'd be a hassle to make up a bunch else statements filled with a billion and/or checks. Instead, you can assign all these states of your character to their own state. What B will do is based on what state you are currently in, with certain actions changing said state. If you want a new feature that B can do, instead of updating all of those else statements, you can add a new state to fit that context. It's a good example of why these types of patterns are helpful. While it might be nice to stick with the straightforward approach, design patterns will keep things smooth in the long run. Plus, the more you apply them, the better you get at using them, and suddenly even problems you've never seen before you can see the pattern underneath.