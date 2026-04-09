---
title: 'Innerwhale default ennemy'
description: 'blog_post_innerwhale_1'
pubDate: '03.26.2026'
heroImage: '/manta.png'
---


In this blog post, we’ll take a closer look at the basic enemy in InnerWhale. This creature, a hermit crab, is one of the first challenges players will face in this combat-puzzle game

---
### 1. Ennemy design

Our enemy design process begins with defining a strong base. The hermit crab was built as a foundational enemy, intended to scale into more advanced variants as the game progresses. As with all enemies, it is designed around the grappling hook mechanic and can be pulled toward the player. In its initial state, it appears without a shell and exhibits simple behavior: moving directly toward the player and attacking once within attack range.

![blog placeholder](/Ev1.png)

Both the second and third variants introduce a shell mechanic, rendering the enemy invulnerable until the player removes it with the grappling hook. Their behaviors diverge once disarmed: version 2 permanently loses its shell and reverts to the base enemy type, whereas version 3 drops the shell in the environment and prioritizes recovering it, temporarily disengaging from combat.

<video class="video-gif" autoplay loop muted playsinline>
  <source src="/Ev3.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

### 2. programation

Working on this project was my first experience with Unreal Engine. Throughout the process, I progressively discovered and learned new techniques that were completely unfamiliar to me at the start.

