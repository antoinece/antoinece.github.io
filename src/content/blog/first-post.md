---
title: 'Physics Engine'
description: 'Lorem ipsum dolor sit amet'
pubDate: '11.18.2024'
heroImage: '/vroum.jpg'
---

### What is Vroum Engine?

Vroum Engine is a small physics engine made in C++ .

### What does Vroum Engine do?

In Vroum Engine, you can:
- Apply forces to an object. 
- Apply forces to an object.
- Set an object as a trigger.

## How does Vroum Engine apply forces?

Vroum Engine uses a custom Vector2D class to apply forces. In this scene, which simulates a solar system using gravity and an initial angular force, we can see planets orbiting around a sun.

---
<video controls style="width: 100%; height: auto;">
  <source src="/solar_systeme.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>

## How does Vroum Engine handle collisions?

Initially, it checks collisions between each object and every other object. This is done for all objects.

---
<video controls style="width: 100%; height: auto;">
  <source src="/colision.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


Then, we implemented a Quadtree, which divides the screen if there are too many shapes. It keeps dividing itself until there is a predefined number of shapes inside each section, and then it checks collisions for each part of the Quadtree individually.

---
<video controls style="width: 100%; height: auto;">
  <source src="/quadtree.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


## How does Vroum Engine manage triggers?

Triggers are an option that a shape can have to detect if any other shape is touching the trigger shape. In this scene, we see shapes turning red when touching an other shape.

---
<video controls style="width: 100%; height: auto;">
  <source src="/trigger.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>


## Test

To test the engine, we tried the solar system simulation with collisions, and here are the results.

---
<video controls style="width: 100%; height: auto;">
  <source src="/solar_colision.mp4" type="video/mp4">
  Votre navigateur ne supporte pas la lecture de vidéos.
</video>

[Project Github](https://github.com/SAE-Geneve/vroum_engine)
