---
name: Safe Space
tools: [Unity, C#, Tools Programming]
image: https://i.imgur.com/dRjxMQu.gif  # One static thumbnail and one animated thumbnail locally.
description: A hair-raising exploration - interactive story.  # 2022
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/aC3OcyFzxpk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/pD1R_6gKtMk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2022.04
##### Role: Lead Game Programmer

As the lead game programmer, I worked on the following:

* Gameplay Programming
    * Implemented and programmed five out of seven scenes that are in the game, which are the main menu and sessions one and three (two scenes for each session gameplay).
        * Programmed player movement and controls.
        * Set up animations, interactions, cutscenes, etc.
    * Set up the connections and transitions between the scenes to establish the overall game flow.

* Systems Programming
    * Developed custom timeline extensions to improve cutscene creation workflow.
    * Designed and programmed the core underlying event-based interaction system and the room transition system that power all of the scenes. This immensely helped to increase the productivity of the game programming process by minimizing the code that the programmers have to write.
    * Created custom editor scripts (e.g., volumetric random object placer) and GUI for a faster and more intuitive workflow.
    * Programmed custom shaders to make 3D lighting and post-processing work correctly with sprite renderers.

* Technical Art
    * Was responsible for most of the rendering-related work, such as setting up post-processing effects, lighting, UI, etc.

<br>

<!-- Abstract / About -->
#### About

Safe Space is a hair-raising exploration - interactive story where the player is a therapist whose job it is to help a 6 year-old child uncover the source of their trauma. To do this, the player will travel through the mind of the child and meet key characters from the child's past through their disturbing point of view. The player will dive deeper into the child’s mind as the story goes on.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Designing Event-Based Systems

<center>
    <img src="https://i.imgur.com/lU3Vkk6.png"/>
</center>

Previously, when developing linear story-based games similar to this project, I used to write lots of very specific code that was only used in very specific situations. The result was that design iterations took longer, and organizing and debugging code was more difficult.

So when we started working on this project, I thought we should have generic, robust systems that could be used to handle a large number of common scenarios as well as in smaller, specific ones without needing to write a lot of additional, redundant code.

As a result, I chose to adopt an event-based design for the core systems used in this project, such as the interaction system, input action detection system, room transition system, and player behavior. As a result of this design choice, not only did it reduce the amount of code that had to be written to implement the gameplay, it also made the systems much more extensible, making it way easier for programmers to extend the functionalities of the systems. To implement these systems, I made extensive use of UnityEvents and C# events.

##### Interaction System

<center>
    <img src="https://i.imgur.com/lMoEnPi.png"/>
</center>

The most prominent use case of this design is the interaction system.

The interaction system was designed and built for use in all scenarios in which we need to have certain events to happen when certain conditions are met and a triggering event occurs.

Thanks to its versatility, the system was used to implement a lot of gameplay.

By enabling us to implement interactions and gameplay with little to no code, the system really helped for faster development and quick design iterations since making changes only required a few clicks.

<br>

#### Custom Editor GUI & Editor Scripts

<center>
    <img src="https://i.imgur.com/5bQ8Urn.png"/>
    <img src="https://i.imgur.com/RyiTaMm.png"/>
</center>

To make the workflow faster and more intuitive, I created custom editor GUI and custom editor scripts.

<br>

#### Customizing and Extending Timeline and Playables

<center>
    <img src="https://i.imgur.com/EqHxooO.png"/>
</center>

Because our game had multiple cutscenes and pre-scripted sequences, we extensively used Unity timelines.

Since I wanted to do more with timeline, I ended up creating custom extensions such as a track that overrides and blends transforms, a track that shakes objects, and a marker signal to replace timeline signals (that I did not enjoy using) that send out event signals that can be handled using UnityEvents.

<br>

#### Technical Art and Art Direction

<center>
    <img src="https://i.imgur.com/NJOeWit.png"/>
    <img src="https://i.imgur.com/VQ2buOs.png"/>
</center>

One of the most praised aspects of our game was its unique and consistent aesthetics and atmosphere.

To make these visuals possible, I was in charge of everything related to technical art, such as setting up post-processing effects, lighting, and particle effects.

Besides setting up effects and lighting, one crucial work was writing custom shaders. We faced an issue where the shader of the default sprite renderer material didn't work correctly in our game that took place in a 3D-navigational environment and also had post-processing effects that relied on depth. To solve this problem, I had to write a custom shader to make 3D lighting and post-processing work correctly with sprite renderers.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Links

**[Link to itch page](https://briefjoe.itch.io/safe-space)**