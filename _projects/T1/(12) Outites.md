---
name: Outites
tools: [Unity, C#, Procedural Generation]
image: https://i.imgur.com/VigYfW2.jpg  # One static thumbnail and one animated thumbnail locally.
description: # 2018  # Procedurally generated planet colonization simulation.
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/C9iIGnywQvs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2018.08
##### Role: Co-Director, Game Programmer, Game Designer

As a co-director and the sole programmer, I was responsible for the overall creative vision of the project and the entire technical implementation using Unity with C#.

<br>

<!-- Abstract / About -->
#### About

**Background**

Since I was a child, my dream was to travel the universe and to boldly go where no one has gone before. Planets full of wonder, mysterious alien creatures, and breathtaking civilizations. I wanted to express these beautiful and charming experience of exploration as a video game.

<center> 
    <img src="/assets/img/projects/reg/syd-mead-1.jpg"/>
    <img src="/assets/img/projects/reg/syd-mead-2.jpg"/>
    <p><small>Concept arts from Syd Mead</small></p>
</center>

**Designing the Game**

The design goal of the project was to make a game that is different from typical mobile games and make it as innovative and experimental as we can. Usual mobile games are small in scale (compared to PC games), consist of repetitive gameplay, and quantitates success using scores. I wanted to break these general rules of mobile games.

**What is Outites?**

Outites is a game where the player becomes the explorer, discovers unknown planets, and transforms the planet using resources.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Procedurally Generated Planets

We wanted the player to have a new experience every time they discovered a new planet. The planet generation system in Outites use 3D simplex noise to create billions of unique planets. Each world has a different combination of resource reserves, topography, colors in the environment, and the placement of natural elements. Using a custom shader, the color of the planet's surface changes dynamically by it's altitude, visually highlighting the planet's topology and depth.

<center>
    <img src="/assets/img/projects/reg/outites-generation.gif"/>
    <p><small>Planets being generated</small></p>
</center>

<br>

#### Collecting Resources

In the process of mining (deforming the planet), the player can obtain underground mineral resources such as stones, gold, copper, and iron. The mining probabilities are unique to each world. 

<center>
    <img src="/assets/img/projects/reg/outites-mining.gif"/>
    <p><small>Mining</small></p>
</center>

With the collected resources, players can construct buildings. Each building generates resources at a certain time, with the rate being determined by the fertility of the planet and the degree of wind blowing.

<center>
    <img src="/assets/img/projects/reg/outites-construction.gif"/>
    <p><small>Constructing buildings</small></p>
</center>

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Awards

Outites won the **Gold Prize (2nd Place) in the 2018 Annual Sunrin Internet High School Mobile Content Competition**.