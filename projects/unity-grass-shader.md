---
layout: project
type: project
image: images/grassscene.png
title: Unity Grass Shader
permalink: projects/grass
# All dates must be YYYY-MM-DD format!
date: 2024-05-10
labels:
  - Unity
summary: Procedurally animated grass in Unity
---

<img class="ui medium right floated rounded image" src="../images/grass.gif">

Created for my final project for a computer graphics class, this grass is made using HLSL shader code. The code is excuted on the GPU and draws blades of grass over a canvas that I 3D modeled in Blender.

The animation of the grass uses a my own custom perlin noise function which allows the grass to blow in a random yet smooth manner.

<img class="ui medium right floated rounded image" src="../images/noise.png">

By exposing variables to the unity editor I can change various properties of the grass on the fly.

Check out a demo video <a href="https://drive.google.com/file/d/1C1jSkhTgfmfDqIGWXnHTHS_yJPbRoIxc/view?usp=drive_link">here</a>
