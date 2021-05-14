---
name: Captain on the Bridge
tools: [Unity, C#, Deep Learning, Experimental]
image: /assets/img/projects/thumbnails/cob-tn.jpg
description: # Top-down space shooter
---

<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/D8L49wHhZc4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

##### Role: Director, Game Designer / Programmer
##### Genre: Action, Shooter
##### Date: 2017.10
<br>

#### Background

I'm a big fan of Star Trek, a famous Sci-fi TV series. Watching the spaceship Enterprise traveling through space, I dreamed of myself being the captain, commanding the spaceship myself. I wanted to make this fantasy into a game and also wanted to differentiate it from the gameplay that was often tried. So I decided to make an experimental game using machine learning.

<center> <img src="/assets/img/projects/reg/star-trek.jpg" width="420" height="236"/> </center>

Captain on the Bridge is a game in which the player becomes the captain of the ship. The goal is to survive the attack of enemy ships. The weapon system of the enemy ship is controlled by an AI trained on the data played by a human player. The player must play the game with strategic moves and judgments.

#### AI System with Deep Learning

Instead of using a rule-based AI system, The weapon targeting system of both the enemy ship and the player's ship is controlled by a trained AI based on the data played by a human.

#### Fully Physics-Based Enemy Guidance System

Until now, I have been developing pathfinding AI only in games with surfaces, so we had to make a new navigating AI because the game has no such surface. The navigation system predicts the ship's future position, and based on the prediction, the system calculates the amount of propulsion needed to maintain a good position to fight with the enemy.

<center> <img src="/assets/img/projects/thumbnails/cob-tn.jpg" width="648" height="405"/> </center>