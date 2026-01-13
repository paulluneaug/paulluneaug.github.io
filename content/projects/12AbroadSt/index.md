---
draft: true
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
**Duration :** 4 months {{< br >}}
**Team size :** 10 {{< br >}}
**Role :** Gameplay, System & UI Programmer, Tech Artist

## Pitch

12 Abroad St. is a text based RPG

## Technical overview

For this project, my duties are :

- Implementing and architecturing the **interaction system**, trying to make it as **extensible** as possible 
- Developping tools to **import and edit the tables**
- Building and integrating the **UI** of the game
- Helping our tech artist create the **ASCII shader**
- Integrating assets (UI, animations, VFXs, )
- Proposing and enforcing **coding standards** to ensure consistency in the source code
- Reviewing code and pull requests on GitHub to make sure the project stays clean
- Planning and estimating all the programming tasks to be able to anticipate and make sure the scope is achievable

### The ASCII shader

The game really focuses on writing and text and we didn't want the player to focus too much on the illustrations. This two pillars led us to use ASCII art for the illustration to make them "fuzzy".

But instead of making each illustration by hand, we chose to use a **shader to transform the output of a camera into an ASCII illustration**.

### The Git workflow

Git is one of our most important tools, and using it properly can prevent many problems (data loss, conflicts, ...).

That is why we decided to impement a Git workflow based on pull request so that the assets and code that end up in the main branch are always tested reviewed.

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

## Gallery

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