---
layout: project
type: project
image: img/arcade/arcade_project_logo.jpg
title: "Arcade Game"
date: 2021
published: true
labels:
  - Game Development
  - Coding
  - Java
summary: "My team created a replica of an arcade game called Joust origionally from the '80s using Java"
---

<div class="text-center p-4">
  <img width="200px" src="..img/arcade/arcade_project.jpg" class="img-thumbnail" >
</div>

### Remaking Joust in Java

I've always been a fan of classic arcade games, so when I had the opportunity to remake a simpler version of Joust in Java for a project, I was excited to get started.

Joust is a two-player game where players control knights on ostriches, trying to knock each other off of their mounts. The game was released in 1982 and was one of the most popular arcade games of its time.

We quickly realized that we would need to make some smart choices about the algorithms we used, or else the game would be too slow to play. For example, we decided to draw the game objects based on individual objects in a scene, rather than trying to rasterize them all at once. This made the game much faster, but it also required us to do more work to keep track of the objects' positions and rotations.

We also had to make some decisions about the features of the game. We decided to make a single-player version of the game with fewer transitions and without lots of weapons. This made the game easier to develop, but it also made it less complex and challenging.

For this project, my partner and I started by brainstorming how we could simplify the game while still keeping the core gameplay mechanics intact. We decided to focus on the single-player mode and remove some of the more complex elements, such as the ability to pick up weapons.

The first few weeks of the project were spent learning the basics of Java and how to create graphics and animations. We also had to learn about algorithms for collision detection and pathfinding.

Once we had a basic understanding of the concepts, we started working on the game's code. We quickly realized that the program was very slow, since we were trying to rasterize all of the graphics. We fixed this by switching to drawing based on individual objects in a scene.

Here are some of the specific challenges we faced and how we overcame them:

Making the game fast enough: The original Joust game was designed to run on arcade machines with very limited hardware. We needed to make sure that our Java version of the game could run smoothly on modern computers. We did this by using efficient algorithms for drawing the game objects and by optimizing the code as much as possible.

Keeping track of the game objects: The original Joust game has a relatively small number of game objects. Our Java version of the game has a much larger number of objects, which made it more difficult to keep track of their positions and rotations. We solved this problem by using a data structure called a "scene graph" to organize the game objects.
Deciding on the features of the game: We had to make some tough decisions about which features to include in our Java version of Joust. We wanted to make the game as faithful to the original as possible, but we also wanted to make it playable on modern computers. In the end, we decided to make a single-player version of the game with fewer transitions and without lots of weapons.
