---
draft: false
title: "OnionMan"
highlight: true
tags: ['Unreal Engine', 'C++', 'Unity', 'C#', 'Network', 'Gameplay', 'Tools']
publishDate: 2022-11-01

---

### Overview

**Platform :** PC and mobile {{< br >}}
**Duration :** 6 months {{< br >}}
**Team size :** 6 {{< br >}}
**Role :** Network, Gameplay & Tool Programmer

## Presentation

OnionMan is a two-player asymetric cooperative game where one of the player plays a shoot-'em-up on desktop while the other plays a management game whose gameplay is inspired by [FAR: Lone Sails](https://store.steampowered.com/app/609320/FAR_Lone_Sails/) on their mobile.

## Technical overview

For this project, my duties were :

- Building a custom **Unity - Unreal Engine network protocol**
- Designing the level architecture to make it flexible and expandable
- Creating an Unreal Engine editor **tool to help level design**
- Implementing the enemies and boss behaviour
- Creating simple VXFs using Niagara

### Languages used

This project was created using **Unity** and **Uneal Engine** and therefore used **C#**, **C++** and **Unreal's Blueprints**.

### The Network protocol

For this project I wanted to learn more about network so I decided to make my own custom protocol. It works be synchronizing variables between the two engines via TCP.

Whenever changed, the synchonized variales values are encoded and sent to the other engine. The protocol is simple and does not feature more advanced techniques like anticipation or any kind of network security as it wasn't really neccessary for our usage.

Retrospectively, I'm not sure it was the best idea to start from scratch given the time and constraints we had but I had fun and I learned a lot making it.

## The team

- **Yannis ARIBOT** - 3D & Tech artist
- **Florent BASCOUL** - Game designer
- **Léo CEELEE** - Composer
- **Victor DE SENNEVILLE** - Project manager & programmer
- **Paul LUNEAU** - Programmer
- **Élodie PRUDENT** - Narrative designer

## Links

{{< button href="https://paulluneau.itch.io/onionman" target="_blank">}}
{{< icon "itchio" >}} Itch.io
{{< /button >}}

{{< empty-p >}}

{{< itchio id="2455869" linkback="true" dark="true" >}}

{{< empty-p >}}

{{< button href="https://github.com/OnionMan-contre-les-nuggets-de-lespace/OnionMan-contre-les-nuggets-de-lespace" target="_blank">}}
{{< icon "github" >}} GitHub Repository
{{< /button >}}

{{< empty-p >}}

{{< github repo="OnionMan-contre-les-nuggets-de-lespace/OnionMan-contre-les-nuggets-de-lespace" showThumbnail=false >}}