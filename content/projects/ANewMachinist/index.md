---
draft: false
title: "A New Machinist"
cover: /images/projects/covers/ANewMachinist.png
alt: "A New Machinist cover"
description: " "
tags: ['Unity', 'C#', 'C++', 'C', 'Arduino', 'Electronics', 'UI', 'Tools']
highlight: true
publishDate: 2025-03-01
---

### Overview

**Platform :** PC {{< br >}}
**Duration :** 3 months {{< br >}}
**Team size :** 8 (and 2 additional persons) {{< br >}}
**Role :** Electronics, Gameplay, UI and Tool Programmer

{{< figure
    src="images/Installation.jpg"
    alt="Installation"
    class="center-img width-60"
    >}}

## Presentation

Play the role of a puppeteer candidate at a puppet theatre. Learn how to use your console to control the stage and follow the director's instructions or improvise based on the elements you give him.

The original experience is played with a **physical console** that we built. It features no less than 17 buttons, 9 switches, 3 rotary encoders, 3 potentiometers, 4 faders (one of which is motorised) and 22 LED indicators!

{{< figure
    src="images/Gameplay.jpg"
    alt="Gameplay"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

## Technical overview

For this project, my duties were :

- **Crafting the console** and interfacing it with Unity using a custom protocol (electronics, soldering, wiring, wood and metal working)
- Implementing the User Interface and making it fully navigable using only 3 buttons
- Implementing multiple interaction with the objects on the stage (boxes dropping items, moving set, lights, curtains...)
- Helping to implement the dialogue and act integration tool
- Integrating the artists assets (UI, 3D models, animations...)
- Being responsible for the **Git workflow** to prevent any major conflicts
- Working with the sound designer to add hooks in the code to trigger audio events

### Languages used

This project was created using **Unity** and therefore used **C#** as well as **C++** and **C** for the Arduino code.

### The console

{{< figure
    src="images/Console.jpg"
    alt="A picture of the console"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

One of the main challenge in this project was to craft from scratch a working console and to connect it with Unity as I had very little experience with elecronics and had never use that many components.

The whole circuit is built arround an [**Arduino Due board**](https://docs.arduino.cc/hardware/due/) that has 66 pins for us to use, a lot more than the average Arduino. Still, it wasn't quite enough for all the components we wanted to control so I had to make a clever usage of **multiplexers** to be able to connect even more components.

I had also did not anticipate that **power would become an issue** (for the LEDs especially) as my previous projects were a lot smaller and the board could easily power all the components on its own. {{< br >}}
For this project, **the board does not power any LED** but instead controls **transisors** that let the current of an **external power source** flow. 

The finished console works quite well thanks to the time I put into it, but I hope I never have to fix the mess underneath it.

{{< figure
    src="images/Console_Bottom.jpg"
    alt="A picture of the bottom of the box, with wires everywhere"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

## The team

- **Tanguy BRUSCHI** - Sound Designer & Composer
- **Edouard CHAANG** - Additional Programming
- **Justine DESMEDT** - Game Designer, Narrative Designer & Writer
- **Matthieu GOLSENNE** - Game Designer, Narrative Designer, Additional Writing & Additional Programming
- **Tom JAMGOTCHIAN** - Voice Actor
- **Paul LUNEAU** - Programmer
- **Gensana MANCEAU** - Producer & Additional Writing
- **Daphné RENAULD** - Texture Artist
- **Gabin ROHDE** - Game Artist
- **Natanael ROSSIGNOL** - Game Artist

## Trailer

{{< youtube yBrdwWxM35k >}}

## Links

{{< button href="https://brs-t.itch.io/a-new-machinist" target="_blank">}}
{{< icon "itchio" >}} Itch.io
{{< /button >}}

{{< empty-p >}}

{{< itchio id="3654109" linkback="true" dark="true" >}}

{{< empty-p >}}

{{< button href="https://github.com/paulluneaug/HelpingHand" target="_blank">}}
{{< icon "github" >}} GitHub Repository
{{< /button >}}

{{< empty-p >}}

{{< github repo="paulluneaug/HelpingHand" showThumbnail=false >}}