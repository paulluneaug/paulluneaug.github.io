---
draft: false
title: "Popo Deglingo"
cover: /images/projects/covers/PopoDeglingo.png
alt: "Popo Deglingo cover"
description: " "
tags: ['Unity', 'C#', 'Arduino', 'Electronics']
publishDate: 2025-09-02
---

### Overview

**Platform :** PC {{< br >}}
**Duration :** 5 days {{< br >}}
**Team size :** 10 {{< br >}}
**Role :** Electronics, Gameplay Programmer


## Pitch 

Popo Deglingo was a temporary physical installation set for an accessibility workshop. We were tasked with making a game playable by visualy impared people, and this is what we made :

{{< figure
    src="images/installation.jpg"
    alt="Picture of the installation"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

In Popo Delingo you play as an aspiring alchimist taking care of their master's shop during their absence, which mean receiving clients and preparing the potions they are asking.

{{< figure
    src="images/grimoire.jpg"
    alt="Picture of the secondary screen with the grimoire"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

When asked for making a potion you can check its recipee in your grimory, giving you clues about its ingredients, which can be how they smell, or how the recipient their in feel when touched.

{{< figure
    src="images/bottles.jpg"
    alt="Picture of all the textured bottles"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

Then you have to pickup the right ingredients, each potion being composed of three of the twelve available. Place them on the pedestals in front of the client to validate the potion, before receiving your next client.

{{< figure
    src="images/customer.png"
    alt="Drawing of a customer"
    class="width-100"
    containerClass="width-60 center-img"
    >}}

The goal is to satisfy the most clients possible in 5 minutes, after which the game end, your master coming back home.

## Technical overview

To allow the bottles to be recognized by the game, we stuck **NFC tags** at the bottom of the bottles that could be identified by **NFC readers** in the pedestals.
Those readers were controlled by **Arduino Uno boards** that then sent datas using a **custom protocol** to a computer running the game on **Unity**.

For this project, I was tasked with interfacing the Arduino boards to Unity and helping make the NFC readers work.

## The team

- **Paul LUNEAU** - Programming & electronics
- **Arthur ALAIN** - Programming, electronics & voice acting
- **Julien OUDOT** - Programming, electronics & voice acting
- **MaÏa ESQUERRE** - 2D artist
- **Leonard TAMAS** - Sound design & composing, voice design & acting
- **Jade BRUNEAU** - Dialogue writing, voice acting & installation
- **Gabin ROHDE** - Dialogue writing, voice acting & installation
- **Samy DIF** - Playtest,  voice acting & installation
- **Madeleine MÉRANGER** - Game design, voice acting & installation
- **Timothée DRUGEON** - Game design, voice acting & installation

## Links

{{< button href="https://cybertoasty.itch.io/popo-deglingo" target="_blank">}}
{{< icon "itchio" >}} Itch.io
{{< /button >}}

{{< empty-p >}}

{{< itchio id="3916586" linkback="true" dark="true" >}}

{{< empty-p >}}

{{< button href="https://github.com/paulluneaug/PopoDeglingo" target="_blank">}}
{{< icon "github" >}} GitHub Repository
{{< /button >}}

{{< empty-p >}}

{{< github repo="paulluneaug/PopoDeglingo" showThumbnail=false >}}