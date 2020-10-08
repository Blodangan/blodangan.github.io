---
title: Voxel World
image:
    path: /assets/projects/voxel-world/screenshot.png
    width: 1280
    height: 720
datetime:
    from: 2015-08
    to: 2015-08
tags: C OpenGL SDL
description: A simple voxel project.
---

Inspired by [Minecraft](https://www.minecraft.net/), I wanted to recreate the feeling of a cubic world while learning OpenGL.

The world is divided in 16x2x16 chunks containing 16x16x16 blocks.

{:.mb-0}
Features:
* Perlin noise terrain generation
* chunks frustum culling
* chunks distance culling
* chunks VBO rebuilt when needed
* hidden faces removed from VBO
* [ambient occlusion](https://0fps.net/2013/07/03/ambient-occlusion-for-minecraft-like-worlds/)
* skybox
* fog
* camera as in Minecraft flying mode
