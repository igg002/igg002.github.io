---
name: Genscapes
tools: [Unity, C#, Python, Deep Learning, Procedural Generation]
image: https://i.imgur.com/enT4EDV.gif  # One static thumbnail and one animated thumbnail locally.
description: A tech demo on AI-powered procedural landscape synthesis.  # 2021
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/yoEOlKosVeU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2021.12
##### Role: Sole Developer

As the sole developer, the project was developed entirely by myself from design to programming.

<br>

<!-- Abstract / About -->
#### About

Project Genscapes is a proof-of-concept tech demo on AI-powered procedural landscape generation. Inspired by AI-driven content creation tools such as Runway and Artbreeder, the demo uses a custom neural network model to synthesize realistic-looking landscapes.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Serverless Deployment

Instead of running the model offline, I decided to deploy the model by using cloud service providers. I wrote Python code to receive HTTP requests, handle and process input data, run model inference, and send the results back to the client. I then packed the models and the code into a Docker image and deployed it using AWS Lambda.

<br>

#### Fully Responsive UI

<center>
    <img src="https://i.imgur.com/nWOeHQs.png"/>
</center>

Using anchors, pivots, layout groups, etc., I made the UI fully relative and responsive.

<br>

#### Building the Model

Using multiple publicly available geographic data sources, I created a custom heightmap dataset with more than 200,000 data points from the ground up.

To ensure the dataset's quality, an automatic data filtering pipeline using noise estimation was built and used to remove blurry and noisy data.

To train the generative heightmap model using this custom dataset, I created and used a modified StyleGAN2 model to make it support 16-bit grayscale image training.

<br>

#### Latent Space Exploration

The demo features a variety of intuitive methods of exploring the latent space.

##### Random Generation

<center>
    <img src="https://i.imgur.com/Jx4CpIx.gif"/>
</center>

Pressing run with an empty grid executes random generation, filling the grid with random samples. This is the most basic and straightforward way of retrieving samples.

The truncation value parameter controls the quality and variety of the sampled heightmaps. Higher truncation values result in more diverse samples, while lower truncation values result in better quality samples.

<br>

##### Proximity Search

<center>
    <img src="https://i.imgur.com/tF7NTHa.gif"/>
</center>

Similar samples with a specific heightmap can be found using proximity search. Loading a heightmap sample into the center item of the grid switches the mode to proximity search.

The search distance parameter determines how similar you want the samples to be to the loaded heightmap. Higher distances result in less similar heightmaps being sampled.

<br>

##### Grid Interpolation

<center>
    <img src="https://i.imgur.com/YEwykJd.gif"/>
</center>

Interpolate between four samples using grid-based interpolation. By loading heightmap samples into the four edges of the grid, the mode switches to grid interpolation. You don't need to load heightmaps for all four edges to use this feature, as edges left blank will be automatically filled with a random sample.

<br>

##### Two-Point Interpolation

<center>
    <img src="https://i.imgur.com/v04Mris.gif"/>
</center>

Blend between two heightmaps using two-point interpolation.

<br>

#### Visualization

<center>
    <img src="https://i.imgur.com/Eq9Buzx.gif"/>
</center>

The demo currently supports four different visualization presets. Press load and select the heightmap you wish to visualize.

<br>

#### Cancelled Features

##### Projection

<center>
    <img src="https://i.imgur.com/sIyJRdG.gif"/>
    <img src="https://i.imgur.com/tite9TF.gif"/>
    <p><small>Projection</small></p>
</center>

Iterative projection of a given image to the latent space was implemented and tested at the research stage. However, it couldn't make it to the tech demo due to server implementation issues.

<br>

##### CLIP Guidance

<center>
    <img src="https://i.imgur.com/sjBv2i0.gif"/>
    <p><small>Result with the text "Desert Dunes"</small></p>
    <img src="https://i.imgur.com/lXOnm6Y.gif"/>
    <p><small>Result with the text "Spikes"</small></p>
</center>

Using [CLIP](https://openai.com/blog/clip/) and differential rendering, a feature for text-to-heightmap was implemented and tested at the research stage but couldn't make it to the tech demo for the same reason as above.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Links

**[Link to playable demo](https://sunny00.itch.io/genscapes)**