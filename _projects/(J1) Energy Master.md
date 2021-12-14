---
name: Energy Master
tools: [Unity, C#, Procedural Generation]
image: https://i.imgur.com/gSNFjTl.gif  # One static thumbnail and one animated thumbnail locally.
description: Energy management city-building simulation.  # 2017
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/N0p7SaJaXVc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2017.07
##### Role: Co-Director, Game Programmer, Game Designer

As a co-director and the sole programmer, I was responsible for the overall creative vision of the project and the entire technical implementation using Unity with C#.

<br>

<!-- Abstract / About -->
#### About

**Background**

Global warming is one of the biggest problems that humanity is facing today. Since the mid-20th century, the increase in CO2 emissions has caused problems such as sea level rise and desertification on Earth. Our team developed this game to inform the environmental damage caused by the indiscreet use of fossil fuel.

<center>
    <img src="/assets/img/projects/reg/fossil-fuel.jpg"/>
</center>

**The Design of Energy Master**

*Energy Master* is a strategy game in which the player builds power stations to increase the score. The player must increase the population to increase the score while producing sufficient energy proportional to the population. Players must balance the construction of environmentally friendly but less energy-efficient energy power stations with energy-efficient non-renewable energy power stations that destroy the environment. The higher the percentage of renewable energy power stations in the total construction, the higher the score, and vice versa.

<center>
    <img src="https://i.imgur.com/gSNFjTl.gif"/>
</center>

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Procedurally Generated Environment

<center>
    <img src="https://i.imgur.com/FdlL9rX.gif"/>
</center>

Instead of handcrafting a single stage, we developed a procedural generation system to prevent repetitive gameplay. The system creates the game stage using a custom cellular automata model. And to determine the wind velocity, solar radiation, and reserve value of each tile, we used 2D perlin noise for natural-feeling numeric distribution.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Awards

Energy Master won the **Grand Prize (1st Place) in the 8th Annual Sogang University MTEC National High School Game Competition** and **Gold Prize (1st Place) in the 3rd Annual Sunrin Internet High School Hackathon**.