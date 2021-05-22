---
name: Corrupt Circuits
tools: [Godot, Shader]
image: https://i.imgur.com/B0QU4VM.gif  # One static thumbnail and one animated thumbnail locally.
description: # 2020  # Fast-paced touch-based arcade minigame mash.
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/MFBTV1bHeQY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2020.09
##### Role: Lead Programmer, Game Designer

As the lead programmer and game designer, I was responsible for the following tasks:
* Designing and programming three out of four minigames (virus toss, ninja, and wash).
* Implementing corruption effects such as glitch shaders and dynamic game speed shifting.
* Designing and implementing the overall minigame instantiating and progress tracking structure.

<br>

<!-- Abstract / About -->
#### About

Corrupt Circuits is a fast paced one-touch game where you attempt to slow down the eventual corruption of your computer by going through a series of arcade-like touch based challenges. You attempt to delay the computer from destroying all of its files and data by playing simple minigames to “rescue” the files. As the progress bar fills up, the computer becomes more corrupted, and effects start to mess with the games.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Glitch Effect Shaders

<center>
    <img src="https://i.imgur.com/ZMT2Ny8.gif"/>
    <img src="https://i.imgur.com/RO2GTk6.gif"/>
    <p><small>Glitch Effects</small></p>
</center>

As the progress bar fills up, the computer becomes more corrupted, and effects start to mess with the games as shown in the above. To achieve glitch post-processing effects, I used Godot's shading language to write four overlay shaders (greyscale, pixelate, chromatic aberration, edge detection) and programmed a system that randomly applies those shaders to parts of the screen.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Links

**[Link to playable demo](https://sunny00.itch.io/corrupt-circuits)**