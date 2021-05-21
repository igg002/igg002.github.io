---
name: Frostbitten
tools: [Unity, C#, Animation, AI]
image: https://i.imgur.com/Brkv0vr.gif  # One static thumbnail and one animated thumbnail locally.
description: # 2020  # Top-down co-op zombie shooter.
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/zG8j_wYU2io" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2020.10
##### Role: Game Programmer

As the sole programmer, I was responsible for the entire technical implementation work using Unity with C#, including tasks such as the following:
* Programming custom look-at and rotation IK systems to achieve convincing and natural-looking player animation.
* Implementing player character controls and behavior.
* Programming the enemy AI behavior (perception, patrol, combat, etc).
* Implementing a spawning system aware of the player's situation for spawning both items and enemies.

<br>

<!-- Abstract / About -->
#### About

Frostbitten is a single-screen 2P co-op zombie shooter where players have to formulate vaccines, while defending themselves from the infinitely spawning zombies in this abandoned place.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Programming Custom IK Systems

<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/fOtEoCVqTTw?playlist=fOtEoCVqTTw&loop=1&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="video">
    <iframe width="322" height="322" src="https://www.youtube.com/embed/ccVLjPPtCsI?playlist=ccVLjPPtCsI&loop=1&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<center> <p><small>Video demonstrating both IK (look-at and rotation) being applied to the player character's model</small></p> </center>

Because Unity's built-in support for humanoid IK could not be applied to the character models created by the artists, I had to create custom IK systems for the player character model. As a result, I created a custom look-at IK solver for handling upper-body aiming animations and a rotation IK solver for realistic lower body rotation according to the upper body's movement.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
