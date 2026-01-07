---
draft: false
title: "SDF Physics"
cover: /images/projects/covers/SDFPhysics.jpg
alt: "SDF Physics cover"
description: " "
highlight: true
tags: ['C++', 'CMake', 'SFML', 'ImGui', 'Physics and collisions']
publishDate: 2025-07-15
---

### Overview

**Platform :** PC {{< br >}}
**Duration :** 4 weeks {{< br >}}
**Team size :** 1 {{< br >}}
**Role :** Engine Programmer

## Project description

SDF Physics is the support I developped to illustrate and test algorithms for a dissertation I made at the end af my first year of JMIN master's degree about [Signed Distance Fields](https://en.wikipedia.org/wiki/Signed_distance_function) (SDFs).

The main goal was to try to detect overlaps between :

- SDFs and points and circles
- SDFs and triangles
- SDFs and other SDFs.

{{< figure
    src="assets/Trigangle_GradientDescent.png"
    alt="Trigangle GradientDescent"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

## Technical overview

### Languages and tools used

For this project, I used the C++ library **SMFL** as well as **ImGui** and **CMake**.

### What I learned

Thanks to this project I got to learn :

- A lot more about SDFs and their many applications
- How to read and write research articles
- How to implement a simple **Verlet physics solver**

## Links

{{< button href="SDFPhysics_Dissertation_FR.pdf" target="_blank">}}
{{< icon "download" >}} Download the dissertation (in French)
{{< /button >}}

{{< empty-p >}}

{{< button href="https://github.com/paulluneaug/SDFPhysics" target="_blank">}}
{{< icon "github" >}} GitHub Repository
{{< /button >}}

{{< empty-p >}}

{{< github repo="paulluneaug/SDFPhysics" showThumbnail=false >}}
