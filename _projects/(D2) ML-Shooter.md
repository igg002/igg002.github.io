---
name: ML-Shooter
tools: [Unity, C#, Deep Learning, Reinforcement Learning]
image: https://i.imgur.com/WdPTcU2.gif  # One static thumbnail and one animated thumbnail locally.
description: An experiment on training a game-playing bot using reinforcement learning.  # 2020
---

<!-- Tech Demo (e.g. Video & Images) -->
<center>
    <img src="https://i.imgur.com/VjfY7bE.jpg"/>
</center>

<br>

<!-- Detailed Role & Date -->
##### Date: 2020.09
##### Role: Sole Developer

As the sole developer, the project was developed entirely by myself from design to programming.

<br>

<!-- Abstract / About -->
#### About

ML-Shooter is a small-sized experiment on training a game-playing shooter bot using reinforcement learning. Using Unity's [ML-Agents toolkit](https://github.com/Unity-Technologies/ml-agents), I trained a shooter bot that successfully performs the difficult task of aiming and shooting a moving target.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Curriculum Learning

I initially tried training the agent in the environment that I designed as a whole, but the agent wasn't able to show good performance due to the high difficulty of the task.

So, I decided to use Curriculum Learning, a training strategy that gradually increases the task to effectively train a machine learning model, by introducing more constraints over time, such as moving the target around more complexly, adding ammo penalties, etc., as the training progresses.

Through a carefully crafted curriculum that I created over lots of trial and error, I was able to successfully train the agent to successfully shoot a speed-varying target using limited ammo.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Links

**[Link to playable demo](https://sunny00.itch.io/ml-shooter)**