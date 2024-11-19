---
title: 'Physique Engine'
description: 'Lorem ipsum dolor sit amet'
pubDate: '11.11.2024'
heroImage: '/vroum.jpg'
---

### What's Vroum Engine ?

Vroum Engine is a small physic engine made in C++ .

### What's in Vroum Engine ?

In Vroum Engine you can :
- apply a forces to an object 
- have colision that uses weight
- set an object as trigger

## How does Vroum Engine apply forces ?

Vroum Engine uses a self made vector2D to apply forces. In this scene that simulate a solar systeme using gravity and a starting force we can see planetes turning around a sun.

---
<video controls style="width: 100%; height: auto;">
  <source src="/solar_systeme.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>
---

## How does Vroum Engine manage colisions ?

At first it check the collisions between an object and all the other objects and do this for evry objects 