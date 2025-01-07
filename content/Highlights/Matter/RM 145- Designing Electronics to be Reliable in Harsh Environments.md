---
title: "RM 145: Designing Electronics to be Reliable in Harsh Environments"
draft: false
publisher: "[[PCB Chat]]"
published_date: 2024-06-18
tags:
---


## Highlights
* [[2024-06-23]] 08:52  One example that comes to mind is the current state of public ev charging stations. Government reports have concluded that up to 25% of public ev chargers are not working at any given time. While there are many reasons for this, 1 may conclude they are not designed and manufactured for the intended climactic operating environment.

* [[2024-06-23]] 08:53  Doctor Kleiner is a global reliability engineering leader with Delphi Electronics and safety and an adjunct professor at Purdue University. He is also a fellow of the American Society for Quality, or ASQ, a certified reliability engineer. Certified quality engineer, and if that's not enough, a six Sigma black belt. He also holds several us and foreign patents and authored multiple professional publications, including two books on the topics of reliability, statistics, warranty management, and lifecycle cost analysis.

* [[2024-06-23]] 08:53  we even joke that all electronics fail failures are mechanical, when you never hear of electron not making to the other side of the wire unless the wire is broken

* [[2024-06-21]] 08:14  But I mean, yeah, it's not 100% true, because we know there's some special IC based failures, like led shop and, and heart care injection, other things, but still, most of the things we see in the field actually kind of a mechanical nature, still, the majority of those things, I remember when I was a kid, I was always under the.

* [[2024-06-21]] 08:18  You made a statement ten years ago where you said reliability engineers are not trained, they are grown. Disgusting. Two questions. Number one, do you still stand by that? And number two, tell me more about what you mean by they're not trained, they're grown.

* [[2024-06-23]] 08:54  Yeah, I mean, I think it's still true. One of the problems is that we don't have too many schools in this country, actually in Europe as well, which actually train reliability engineers.

* [[2024-06-23]] 08:54  I have a whole chapter on how to do Monte Carlo simulation just using Excel, simple Excel spreadsheet, because I'm a big fan of Monte Carlo simulation. Where did the name Monte Carlo come from? Why Monte Carlo? Why not Miami? Monte Carlo? Basically, in Monaco, there's a casino. Yes, yes. Yeah, Monte Carlo. So it's, it's, it's a random. Like, you go and play in a casino and it's all random

* [[2024-06-21]] 08:28  I think another, you mentioned examples of electronics that have to work and defense and aerospace and all of that with Internet of things, with IoT, I'm seeing a proliferation of what IPC would call class one devices, which is gadget stuff, toys, things like that.

* [[2024-06-23]] 09:21  Things that can fail and nobody dies going out into the field failing because they're not built necessarily to higher quality standards or higher reliability standards because they're just class one devices.

* [[2024-06-23]] 09:21  organization called AEC, Automotive Electronics Council. And actually the components we use in the automotive should go through, should meet the requirements.

* [[2024-06-21]] 09:36  And those requirements are pretty harsh. So it's like about thousand temperature cycles x number of hours at high temperature, a lot of tests.

* [[2024-06-23]] 09:21  So, I mean, again, that's just kind of making a long story short. Those are three key things I would be looking at, materials, components and interconnects. And it's funny, sometimes we don't know what kind of interactions we're going to have, particularly if technology is new. And I'm thinking going back to the early days of LED lighting, if I'm remembering the story correctly, and my guests are always good at correcting me if I'm off. But the early days of the LED electronics involved silver, like a silver backing of some sort. And the industry noticed that in certain regions of the world, these LED lights were failing. And I think one of the reasons they were failing was the propagation of tin whiskers. And evidence determined that it was the sulfur in the air in certain regions of the country. And I'm thinking India, in this particular case study, had an alarmingly high level of sulfur in the air, and that reacted with the silver and grew things and caused a failure.

* [[2024-06-21]] 09:43  So, like in the automotive industry, again, we look at certain percentile of a user and that you need to have a lot of data.

* [[2024-06-21]] 09:49  Yeah, I think it's probably better design or better understanding of the environment in which these chargers are going to go.

* [[2024-06-21]] 12:12  I mean, that would be designing for the very unusual. No one's going to be willing to pay the price universally to buy a laptop that can be thrown against a wall.

* [[2024-06-21]] 12:14  I mean, you can argue about, I know, gravel, gravel bombardment, things like that, but temperature cycling, low temperature exposure, high temperature exposure, you have vibration and mechanical shock.

* [[2024-06-21]] 12:17  I mean, halt testing is a little bit different animal because we don't use halt testing for validation, because validation is basically when you have a system in working order, everything is together. And in fact, in the automotive we have DV and PV. DV stands for design validation when you have a prototype, basically, but fully working, fully working prototype and process validation when you have a production intent unit.

* [[2024-06-21]] 12:23  So there's always a question of correlation between the field and the test.

