---
title: "The Phoenix Project (Summary)"
date: 2020-11-07T16:11:49+01:00
draft: false
tags: ["agile", "devops"]
description: "A quick summary of the book The Phoenix Project"
---

So a couple weeks ago I read **The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win**. What really suprised me was how relatable it was; corporate red tape, in-house tribal warfare and dealing with constraints or bottlenecks on a daily basis. 

Most of the book is focused on two things: the types of work we get to deal with on a daily basis and the **Three Ways**.

## What is work?

In the book the main character, Bill, gets asked this question and comes to the following conclusion after a while.

- **Planned work** which can be described as business related projects
- **Internal projects** or migrations and software updates
- **Changes** such as requests based on feedback
- **Unplanned work** or outages and issues

Unplanned work is the type of work we should be careful of and should try to reduce as much as possible. It is prone to be time consuming and can create constraints.

## The Three Ways

In order to reduce this type of work and the constraints that may follow we can implement the *First Way*.

Essentially the **First Way** tells us to look at the entire chain, from business to development to the end user so that we can increase flow. This is done by limiting work in progress and removing constraints. 

- Make work visible using methods such as Kanban boards
- Reduce multi tasking and context-switching
- Divide larger pieces of work into smaller pieces
- Remove bottlenecks such as knowledge hogging or tightly coupled architecture


When we've implemented this principle we can look at the **Second Way** which tells us to continuously improve by creating fast feedback loops between groups in our system.

- Build knowledge by *failing fast*
- Development should go hand in hand with deployment

Lastly there is the **Third Way** which tells us to create a culture of continuous learning by taking risks and dealing with failure. If we've properly implemented the First and Second way this is possible because we've reduced risk to the point where this can be done safely. An example of this is Netflix's [Chaos Monkey](https://netflix.github.io/chaosmonkey/).

## Takeaways

This book showed the importance of having the right mindset and structuring our organisation as such. DevOps has been around for a while but I think its important to look at where its principles come from which this book does excellently. I really enjoyed it for using a relatable story as a background while explaining these principles. Next up, *The DevOps Handbook* to dig in a bit deeper.