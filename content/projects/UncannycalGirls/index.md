---
draft: false
title: "Uncannycal Girls"
cover: /images/projects/covers/UncannycalGirls.png
alt: "Uncannycal Girls cover image with the game logo"
description: " "
tags: ['Unity', 'C#', 'Gameplay', 'Tools']
publishDate: 2024-12-05
---

## Pitch

Uncannycal Girls is a **two-player cooperative shmup** (shoot-'em-up). Each player takes control of a magical-girl-like angel tasked with defeating a visibly hostile fleet of spaceships.

![Image of gameplay with two players facing small alien](images/gameplay_0.png)

Players will be able to **join their forces and fuse**, transforming into a nightmarish form with sinister implications to overcome the toughest enemies...

![Image of gameplay with the two players fused into a nightmarish angel](images/gameplay_1.png)

The game is a school project and was made with a team of 10 in about a week.

![Image of gameplay](images/gameplay_2.png)

## Technical overview

### Languages and tools used

This project was made using **Unity**.

### My contribution to the project

During this project, I mostly was in charge of the level structure, the enemy wave system, and a tool to allow the game designers to edit the levels easily.

### Level structure

The **level** is divided into successive **waves**, each containing several **events** that are triggered at specific times. {{< br >}}
Those events can : 

- Spawn enemies or obstacles
- Enable or disable GameObjects
- Display UI for a given time

In theory, they could do anything, but we didn't need anything else for this project.

### Level design tool

At this stage, the moment when events are triggered is just a variable in the inspector representing the time elapsed since the start of the wave. This makes it difficult to **synchronise multiple events**, a crucial feature in a shoot-'em-up. That's why, despite the limited time available for the project, we took the time to develop a level design tool to help us.

The tool allowed us to load a wave, move the spawned enemies and obstacles, visualize the moment when the events will trigger and so on.

{{< figure
    src="images/editor_wave.png"
    alt="Screenshot of the Unity editor, with a wave loaded"
    caption="View of the tool in the editor"
    >}}

## The team

- **Baptiste DENIS** - Programmer
- **Victor DE SENNEVILLE** - Project manager
- **Thimothée DRUGEON** - Game & Level designer
- **Maïa ESQUERRE** - Charadesigner, 2D & VFX artist 
- **Moumine KONATE** - UR/UX/UI designer
- **Luna KORJANEVSKI** - UI & Background artist
- **Paul LUNEAU** - Programmer 
- **Sacha MENDY** - Game & Level designer
- **Capucine TABLEAU** - 2D artist & Animator
- **Léonard TAMAS** - Sound designer & Composer

## Trailer

{{< youtube xqaoJ3j1Sug >}}

## Links

{{< button href="https://cybertoasty.itch.io/uncannycal-girls" target="_blank">}}
{{< icon "itchio" >}} Itch.io
{{< /button >}}

{{< empty-p >}}

{{< itchio id="3168289" linkback="true" dark="true" >}}

{{< empty-p >}}

{{< button href="https://github.com/paulluneaug/Nano_Equipe6" target="_blank">}}
{{< icon "github" >}} GitHub Repository
{{< /button >}}

{{< empty-p >}}

{{< github repo="paulluneaug/Nano_Equipe6" showThumbnail=false >}}