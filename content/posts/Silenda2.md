---
author:
  name: "Kunal Sharda"
date: 2019-08-04
linktitle: Silenda Development - Part 2
type:
- post
- posts
title: Silenda Development - Part 2
weight: 10
comments: true
tags: ["Silenda", "Dev", "Java"]
series: 
- SilendaDesign
---

## How has progress been?

Unfortunately, due to being fairly busy with my company, [Scintillating](https://scintillating.us), I have not had as much time to work on this project.

However, I have been working on it with my spare time - I will soon reach out to more people/the community to see if anyone is truly interested before delving deeper into graphics development.

Creating the actual functionality in Java is not too terribly difficult, and I have made good progress. However, I am trying to make it as modular as possible, and as such, iterations over my current design may happen over time.

I am mostly creating a generic card, generic token, and generic moves, which are than used in different cards, tokens, and games that can be used and played. The full release of the archictecture diagram will be in next week's entry. Java does handle game state fairly well, and I have not had any problems for as simple an engine as this.

On the flip side, I am using libGDX or more specifically, mini2Dx (a 2D spin off of libGDX, with more specific graphical design for 2D games). So far, the experience has been decent, but there appears to be no great mini2DX tutorial, and even the libGDX tutorials seem a bit low quality (at least the ones that I have been able to access). This isn't a major hindrance, as the documentation is fairly extensive, but I plan to write about how to use mini2DX through my own experience with it. 

As I continue to do work and gain a better understanding of how it works, I will start including the tutorial in my future blog posts.

## Where to from here?

For next week, I will likely have the complete architecture finalized and have finished most of the "engine" part of the game. However, I will continue to post updates even if this goal is not met, which I unfortunately slacked off on a bit in the past few weeks.

Perhaps I should do some more outreach to see if there's anyone who is interested, which is likely why I'll post it sometime on a GameDev forum or the other.

I have also been working on a different project to deal with flashcards and music, so that will come up soon.

## Questions for the readers?

Initially, I was going to go with Coup and War for the PoC games, but I was looking for recommendations - I want to support overall custom card development and file upload, but I wanted more feedback on if that'd be helpful.

Of course, as always, any feedback or ideas would be great to send my way.

See ya next week!