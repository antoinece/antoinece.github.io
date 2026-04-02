---
title: 'innerwhale level design'
description: 'blog_post_innerwhale_2'
pubDate: '03.26.2026'
heroImage: '/LD.png'
---

When I started building levels for InnerWhale, I quickly realized it wasn’t just about making things “look cool.” It was about flow, intuition, and making sure players never feel lost — unless I want them to. Level design became this constant back-and-forth between control and freedom, structure and chaos. In this post, I’ll break down how I approached that balance and what worked.

---

The opening level serves as a tutorial focused on teaching players how to push and pull crates — a core mechanic that will reappear later in the game. Below is an image of what the level looked like during development.

![blog placeholder](/lvl1base.png)
---
The green marker represents the starting point, and the red marker the goal.

The level begins by asking the player to push the first crate, allowing them pass and reposition the second crate and create a passage forward. A corner crate is intentionally misleading, serving as a decoy.
From there, the player clears the way by pushing a third crate, before pulling the final one to access the level’s exit.

![blog placeholder](/lvl1_1stUP.png)
---
The first iteration change focused on the second crate. Playtests revealed that players naturally approached it at close range, which went against our intention of teaching long-distance interaction.

To guide this behavior, we introduced a gap directly in front of the crate. This design prevents close access and subtly forces players to engage from a distance. When pulled, the crate drops into the gap, effectively bridging it and unlocking the path.

![blog placeholder](/lvl1_2ndUP.png)
---
The next iteration targeted the first crate. Playtesting showed that some players defaulted to pulling it, failing to discover the pushing mechanic altogether.

To enforce the intended behavior, a wall was placed behind the crate to block pulling interactions. Additionally, a gap was added behind the crate so that once the crate is pushed, it falls into it and is removed from the puzzle space, preventing any unintended reuse.

![blog placeholder](/lvl1_3rdUP.png)
---
The last iteration addressed the decoy crate. Because the level serves as a tutorial, introducing a misleading element conflicted with its core intention of clarity over challenge.

To resolve this, the decoy was repurposed into a functional element of the puzzle, becoming an additional crate that the player must pull.


![blog placeholder](/finalStage.png)
---
This is the final iteration of the level.

Each change helped align the design with its core purpose: teaching mechanics through clarity and controlled interactions. Unnecessary friction was removed, and every element now reinforces the intended player behavior.


<video controls style="width: 100%; height: auto;">
  <source src="/playLvl1.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


Here’s me playing through the level.

You can see how the crates and paths work in practice, and how the level’s visual design helps the player understand what to do without any text instructions.
