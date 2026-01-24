---
draft: false
title: '12 Abroad St.'
cover: /images/projects/covers/12AbroadSt.jpg
alt: "12 Abroad St. cover with the game logo"
description: " "
highlight: true
tags: ['Unity', 'C#', 'HLSL', 'UI', 'Shaders', 'Compute Shaders', 'Tools']
publishDate: 2025-10-01
---

### Overview

**Platform :** PC for now (Switch and Steam deck planned){{< br >}}
**Duration :** October 2025 - now{{< br >}}
**Team size :** 10 {{< br >}}
**Role :** Gameplay, System & UI Programmer, Tech Artist

## Presentation

12 Abroad St. is a **text-based RPG** that draws from micro-computer RPG games, almost entirely consisting of **interface**.

You play as someone who has to reluctantly **attend a high school reunion party** in their childhood city. They **rediscover these streets** they were sure to remember, **getting lost** while trying to find their way to the 12 Abroad St, where the party is happening.

**Actions and choices rely on using, finding, discarding or combining verbs**, which are collected through exploration, just like items. It’s an invitation to **reflect on language**, discrepancy and on the **search for meaning and identity** in a world that does not always make sense.

{{< figure
    src="images/game_screenshot.png"
    alt="A screenshot of the game interface"
    class="width-100"
    containerClass="width-80 center-img"
    >}}

## Technical overview

For this project, my duties are :

- Implementing and architecturing the **interaction system**, trying to make it as **extensible** as possible to anticipate future requirements
- Developping tools to **import and edit the tables**
- Building and integrating the **UI** of the game
- Helping our tech artist create the **ASCII shader**
- Integrating assets (UI, animations, VFXs, )
- Proposing and enforcing **coding standards** to ensure consistency in the source code
- Reviewing code and pull requests on GitHub to make sure the project stays clean
- Planning and estimating all the programming tasks to be able to anticipate and make sure the scope is achievable

### The ASCII shader

The game really focuses on writing and text and we didn't want the player to focus too much on the illustrations. This two pillars led us to use ASCII art for the illustrations to make them "fuzzy".

But instead of making each illustration by hand, we chose to use a combination of **shaders to transform a 3D scene view into an ASCII illustration**.

Those shaders allows us to iterate much faster because we can :

- move the camera as much as we want
- add animations easily
- play with the lights
- add or move each object of the scene 

without having to recreate all the illustrations.

{{< figure
    src="images/ascii_eye.jpg"
    alt="An image of an eye in the opening of a door and the same image after the ASCII shader post process"
    caption="The scene view with and without the ASCII shader"
    class="width-100"
    containerClass="width-80 center-img"
    >}}



### The Git workflow

Git is one of our most important tools, and using it properly can prevent many problems (data loss, conflicts ...).

That is why we decided to impement a Git workflow based on pull request to make sure that all the assets and code that end up in the main branch are always tested reviewed.

Let's say you start the Jira task "UI Integration" with the ID "TAS-12", the workflow proceeds as follows : 

- Create a branch from the `main` branch named `TAS-12_UI_Integration`
- Commits in this branch until the task in completed
- Merge the `develop` branch in yours
- Create a pull request to `develop`
- Someone else reviews and tests the changes made
- If everything is approved by the reviewer, they can merge the pull request
- **At the end of each sprint** (about 2 weeks), a **build** is made on `develop` and tested
- If everything still works, the `develop` branch is merged in `main`

This also allows us to have a version that is **always playable** on the `main` branch.

{{< figure
    src="images/git_workflow.jpg"
    alt="Diagram of the git workflow"
    caption="The Git workflow we use"
    class="width-100"
    containerClass="width-80 center-img"
    >}}

## The team

- **Victor DE SENNEVILLE** - Project manager
- **Jules QUIRIN** - Sound designer
- **Paul LUNEAU** - Gameplay, Tools & UI programmer
- **Matéo AVVENTURIERO** - Gameplay & UI programmer 
- **Moumine KONATE** - UR/UX/UI designer
- **Luna KORJANEVSKI** - UI & 2D artist
- **Amandine KLINGER** - 3D & Tech artist
- **Gabriele ENNAOUAJI** - 2D & concept artist
- **Tom JAMGOTCHIAN** - System designer
- **Léa DANTEC** - Narrative designer

## Links

{{< button href="https://cloudcastleaudio.itch.io/12-abroad-street" target="_blank">}}
{{< icon "itchio" >}} Itch.io
{{< /button >}}

{{< empty-p >}}

{{< itchio id="4122318" linkback="true" dark="true" customStyle="bg_color=000000&fg_color=ffffff&link_color=ffff00&border_color=333333" >}}