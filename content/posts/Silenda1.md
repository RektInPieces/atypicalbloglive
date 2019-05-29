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
When we thought about games to implement, we initially were stumped. However, we then realized: why not let the user implement any game?

Thus, Silenda was born: a generic card game building platform. At its core, I am trying to create a simple, yet modular custom card game builder with data integrity and speed being a large part of its design. While I do this, I'd like to release weekly updates on progress, even if it's a simple: "no progress has been done this week." Of course, if anyone is interested in such a project, feel free to contact me at my email on the homepage or leave a comment and I'll get back to you.

The name was chosen as, in Latin, Silenda means silent, which is how I'd like the transactions to be. Full data provenance and privacy would allow for cheating to be minimized, while maintaining the speed and efficiency of transactions.


## Why a card game builder?

Currently, there are only a few projects out there the focus on board game building, and more specifically, card game building. One of the supergiants of this genre is Tabletop Simulator.

However, from my own experiences and of those that I have talked to, the overall control of the game pieces is somewhat terrible, especially for card games.

Further, there really is no good card game builder out there that works on the web nor has a dedicated way to easily create games (including custom functions). I'd say that even Tabletop simulator is somewhat lacking in this sense, although it does have many usable features overall.

As such, and because I play a ton of card games, I thought it'd be a good idea to create a card game builder. I believe that there was one prominent one that had came out earlier called Dulst, but I haven't seen any updates from them nor do I understand how it works, though I hope to see more from it if restarted.

I would say that one that is possible to use on all platforms, perhaps through a simple website or on an app, would be very useful for when cards aren't available or if one wants to play without worrying about managing the game. i.e for games like Mafia, there may need to be a "god" who oftentimes is the first person who gets out as it isn't a very interesting or fun job for most people. 

If that can be handled automatically, then it would be much easier for everyone to play.


## So how are you planning to make it?
Initially, I was trying to use the Oasis Labs game development kit (which has data anonymized), but found it quite difficult to use due to a relative lack of documentation and integration with other games. Given time, I am assuming that the game kit will improve, but it probably isn't going to be fully featured in the scope of this project. Thus, I decided to pivot off of using Rust and React, which are both very problematic to use anyways. 

For a while, I've been wanting to start another project in Kotlin. However, I haven't had much of a chance to do so, and have just used it for work instead of a personal project or two.

As such, it'd be interesting to implement this in Kotlin, which  has an amazing collections library and is built on the JVM. As with most JVM languages, there will probably be some issues with building a decent GUI as JavaFX doesn't look superb, but is probably the best option out there. I have looked into TornadoFX for Kotlin, but I am not sure about what library I should use for that yet and will update later.

It is likely also going to be a webapp that can run on Android, as an app, and on a website for the final product. The cross-platform functionality is something I hope to accomplish for the sole reason of allowing people to play this game remotely without much trouble. I don't know about development for Apple products, but if anyone has experience in that, feel free to point me to anything useful that I can learn.

It will  also be open source so that anyone could help contribute if they so please and comment if I make any errors. I have started to plan it out in a document that I will keep internally for now and will push out some blog posts explaining my rationale, etc. as I go through it.


## What will be some features?

Silenda will truly be a generic card game builder, with some core placements or movements that can be used to create new games or, eventually, I hope to implement Rhai, a Turing-complete embedded scirpting language for more advanced users to build more difficult movements. I will release more information on what the generic card actions are and hwo I envision them being used (i.e for a game like Coup or War).

Initially, I have been working with a standard 52 card deck with jokers, but I hope to make this a platform where custom art can be uploaded and used to create custom cards. The games that I'm building as a demo for the platform are probably going to be War, which is a relatively simple implementation, and Coup, which is a relatively complex game. Those should be coming out by perhaps mid to late July into early August with the current timeframe.

Anyways, there will be another post next week about my progress and it'll become fairly routine after a while. Let me know in the comments if there are any questions or additional feedback that you may have.

See ya next week!