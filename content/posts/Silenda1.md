---
author:
  name: "Kunal Sharda"
date: 2019-05-28
linktitle: Silenda Development - Part 1
type:
- post
- posts
title: Silenda Development - Part 1
weight: 10
comments: true
series: 
- SilendaDesign
---

## What is Silenda?

At its core, I am trying to create a simple, yet modular custom card game builder with data integrity being a huge part of it. And while I do this, I'd like to release weekly updates on progress, even if it's a simple: "no progress has been done this week". Of course, if anyone is interested in such a project, feel free to contact me at my email on the homepage or leave a comment and I'll get back to you.

Initially, to do this, I was trying to use the Oasis Labs game development kit (which has data anonymized), but found it quite difficult to use due to a relative lack of documentation and integration with other games. Given time, I am assuming that the game kit will improve, but it probably isn't going to be fully featured in the scope of this project. 

In Latin, Silenda means silent, which is how I'd like the transactions to be, having no way to cheat in the game, but maintaining speed and efficiency of transactions.


## Why a card game builder?

Currently, there are only a few projects out there the focus on board game building, and more specifically, card game building. One of the supergiants of this genre is Tabletop Simulator.

However, from my own experiences and of those that I have talked to, the overall control of the game pieces is somewhat terrible, especially for card games.

Further, there really is no good card game builder out there that works on the web nor has a dedicated way to easily create games (including custom functions). I'd say that even Tabletop simulator is somewhat lacking in this sense, although it does have many usable features overall.

As such, and because I play a ton of card games, I thought it'd be a good idea to create a card game builder. I believe that there was one prominent one that had came out earlier called Dulst, but I haven't seen any updates from them nor do I understand how it works, though I hope to see more from it if restarted.

I would say that one that is possible to use on all platforms, perhaps through a simple website or on an app, would be very useful for when cards aren't available or if one wants to play without worrying about managing the game. i.e for games like Mafia, there may need to be a "god" who oftentimes is the first person who gets out as it isn't a very interesting or fun job for most people. 

If that can be handled automatically, then it would be much easier for everyone to play.


## So how are you planning to make it?

I've wanted to do another project in Kotlin for a while, especially for fun. However, I haven't had much of a chance to do so unfortunately, and have just used it for other work.

As such, it'd be interesting to implement this in Kotlin, which also has an amazing collections library and is built on the JVM. However, there will probably be some issues with building a decent GUI. Not sure what to use for that yet, but will update on it.

It is likely also going to be a Webapp that can run on Android, as an App or on a website for the final product. I don't know about IPhones, but if anyone has experience in that, feel free to point me to anything useful that I can learn.

It will probably also be open source so that anyone could help contribute and roast me if I make any errors. I have started to plan it out in a document that I will keep internally for now and will push out some blog posts explaining my rationale, etc. as I go through it.


## What will be some features?

Silenda will truly be a generic card game builder, with some core placements or movements that can be used to create new games or, eventually, I hope to implement Rhai, a Turing-complete embedded scirpting language for more advanced users to build more difficult movements. I will release more information on what the generic card actions are and hwo I envision them being used (i.e for a game like Coup or War).

Initially, I have been working with a standard 52 card deck with jokers, but I hope to make this a platform where custom art can be uploaded and used to create custom cards. The games that I'm building as a demo for the platform are probably going to be War, which is a relatively simple implementation, and Coup, which is a relatively complex game. Those should be coming out by perhaps mid to late July into early August with the current timeframe.

Anyways, there will be another post next week about my progress and it'll become fairly routine after a while. Let me know in the comments if there are any questions or additional feedback that you may have.

See ya next week!