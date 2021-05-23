---
name: The Inn at the End of the World
tools: [Unity, C#, AI]
image: https://i.imgur.com/1Nk26PU.gif  # One static thumbnail and one animated thumbnail locally.
description: A relaxing hospitality sim set in a quiet apocalypse.  # 2021
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/mbioGQDOSj0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2021.04
##### Role: Game Programmer

As a gameplay programmer, I programmed the following features of the game:
* Overall gameplay flow management, putting everything together.
* Player character behavior, animation, and controls.
* NPC behavior and data model.
* NPC Dialogue conversion system, gameplay, and UI, actively communicating with writers.
* Cutscenes and visual effects such as post processing.

<br>

<!-- Abstract / About -->
#### About

**A Quiet Apocalypse**

Inspired by games such as *The Stillness of the Wind* and *Ori and the Blind Forest*, the setting of *The Inn at the End of the World* is after the end of human civilization (as we know it), but there aren’t zombies, aliens, or bloodthirsty raiders. Things are just quiet and empty where the player is, as the ruins of humanity’s zenith slowly rust.

**Rebuilding instead of Destroying**

In a desolate space, the goal of the main character is to find human connection. The characters in this game should thus be deeply developed and enticing to interact with for players. The other main goal of the player is building up their inn, allowing it to host more guests. In addition, they need to find better meals for guests and unique materials to allow navigation through the world. 

This game is a combination of visual novel and life-simulator, in the vein of *Harvest Moon*. Playing it is alternately relaxing and intriguing as the character’s stories unfold while the player goes about their business in a strange world. 

The main focus is building up the inn, meeting new characters, and learning about those characters’ stories in order to build up the inn’s reputation. A key part of this is cooking, as each character has specific tastes in food. Fulfilling these tastes nets the best material and reputational rewards.

This game has a stronger emphasis on peacefulness than most post-apocalyptic games. In addition, the main mechanics are intended to promote a slow, relaxing play experience, sort of like a more desolate *Stardew Valley*.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### The Dialogue Conversion Workflow

<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/MswxtzJNzME?playlist=MswxtzJNzME&loop=1&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<center>
    <p><small>The Dialogue Gameplay</small></p>
</center>

<center>
    <img src="https://i.imgur.com/JiUPDJg.jpg"/>
    <p><small>Image of a Spreadsheet Script</small></p>
</center>

Because our game is a very dialogue-heavy game, it was crucial to create a work environment where our writers, who have relatively less understanding of the game's codebase, could easily and quickly integrate and test the characters' dialogue scripts. As I was responsible for the entire NPC and dialogue part of the game, I had to devise a workflow to handle this problem from the early stage of development.

Since I had already decided on a representation model for the character dialogues, I actively communicated with our team of writers and figured out the features they needed. After understanding the needs of the writers, I created and distributed a spreadsheet form that had the features they needed, along with example scripts and guidelines.

With the given spreadsheet format, the writers write scripts according to the form and import them to the project assets folder. Then, the dialogue conversion system automatically converts the scripts into dialogue models used in the game. These scripts not only support simple features such as displaying dialogue lines and changing portrait emotions but also triggering events and setting entry conditions. Through continued iteration and feedback throughout the project, I continuously modified and improved the form and the conversion system.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Awards

The Inn at the End of the World won **Excellence in Narrative, Excellence in Visual Arts, and Audience Choice Award** at **RPI Gamefest 2021**.

<br>

#### Links

**[Link to playable demo](https://lucy-smithers.itch.io/the-inn-at-the-end-of-the-world)**