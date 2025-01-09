---
layout: post
title: "Components & Patterns"
tags:
    - Design system
---
Like many, listening to [Brad Frost](https://bradfrost.com/) talk about [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/) was eye-opening for me. The concept of breaking down a design into its constituent parts that were reusable, and therefore consistently used, really resonated with me and changed how I approched designing digital products.

I must admit though, I have always had a hard time figuring out what the difference between a molecule and an organism is. Worse again was trying to communicate with any conviction those decisions. It seemed that I had to be the one to decide which bucket to put an element because I couldn't clearly communicate the rules. That's not a good way to work. As my friend Larry put it, if I won the lottery tomorrow, someone else will be making these decisions.

Starting with [Global Savings Group (GSG)](https://www.global-savings-group.com/) as the Design System Lead, I was meant to evolve their initial design system and make it scaleable across all of their products. Unfortunately it wasn't very clear to me how to categorize the different elements, nor was it clear for anyone else.

That's when we settled on a much simpiler grouping; components and patterns.

### Clear definitions
Some defining characteristics started resonating with people, and I found it much easier to explain the differences between them.

#### Component
- A component is a  common web interface convention, which is not unique to our products, that the user should reasonably know how to use. Something that just works and we will not waste time reinventing; a button, an input box, a set of tabs

#### Pattern
- A pattern is a group of components composed expressly to solve a user problem that <abbr title="Global Savings Group">GSG</abbr> has deemed important. It is something that is important for <abbr title="Global Savings Group">GSG</abbr> to get right and worth directly user testing and iterating over.