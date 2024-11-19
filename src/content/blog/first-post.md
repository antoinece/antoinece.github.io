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

## How does Vroum Engine manage colisions ?

At first it check the collisions between an object and all the other objects and do this for evry objects 

---
<video controls style="width: 100%; height: auto;">
  <source src="/colision.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


Then we implemented a Quadtree witch divide the screen if their is too much shape inside and keep dividing itself until there is a predefined number of shape inside and then it check collision for each part of the Quadtree individually.

---
<video controls style="width: 100%; height: auto;">
  <source src="/quadtree.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


## How does Vroum Engine manage trigger ?

Triggers are an option that a shape can have to detect if there is any other shape is touching the trigger shape. In this scene we see the shape turning red when the shape are touching each other.

---
<video controls style="width: 100%; height: auto;">
  <source src="/trigger.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


## Test

to try the engine we wanted to test the solar system simulation with collision and their are the results.

---
<video controls style="width: 100%; height: auto;">
  <source src="/solar_colision.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>
