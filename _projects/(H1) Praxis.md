---
name: Praxis
tools: [Python, Deep Learning, JavaScript, React]
image: https://i.imgur.com/VVYO1Hh.gif  # One static thumbnail and one animated thumbnail locally.
description: A cross-platform AI art application.  # 2021
---

<!-- Tech Demo (e.g. Video & Images) -->
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/_h_6MUuYKw8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>

<!-- Detailed Role & Date -->
##### Date: 2020/11 - 2021/08
##### Role: Part Time Software Developer, Machine Learning Engineer

As a part-time software developer and a machine learning engineer, I worked on the following tasks:
* Developed the beta version of Praxis.ai, a cross-platform AI art application, using Electron and TensorFlow.js.
* Wrote public Colab notebooks for educational use in external promotional workshops hosted by the team.
* Conducted research and trained a model for the architecture sketch web demo, and wrote code for interfacing the trained model with the demo.
* Actively participated in the process of designing and planning the products.

<br>

<!-- Abstract / About -->
#### About

Praxis is a cross-platform art application for designers and artists that have no engineering background, powered by machine learning.

<br>

<!-- Technical Features & Challenges & Highlights -->
#### Praxis

##### Training and Integrating an Image-to-Image Translation Model

<center>
    <img src="https://i.imgur.com/JzicXdo.jpg"/>
</center>

Because I was responsible for the application's pix2pix demo section, I had to set up the model, train sample checkpoints, and integrate the model on the client-side. 

For setting up the model structure and training sample checkpoints that users can download and use, I used Python and Tensorflow.

After setting up the model structure in Tensorflow, I built the demo page using React and then integrated the model using Tensorflow.js.

<br>

##### Creating Custom Colab Notebooks for User Customization

<center>
    <img src="https://i.imgur.com/lx5G9sF.jpg"/>
    <img src="https://i.imgur.com/xgEdAu2.jpg"/>
</center>

We wanted to allow users to not only use sample pre-trained checkpoints in the pix2pix demo but also provide a way for them to train their own custom models using their data.

However, because the cost of having a dedicated server to provide this custom training feature was too much for a small team like us, we decided to use Google's Colab service instead.

To that extent, I wrote public colab notebooks that allowed easy dataset creation/preparation and custom pix2pix model training that can export the trained model to load and use in the application once the training is done.

<br>

#### Architecture Sketch Render Web Demo

<center>
    <img src="https://i.imgur.com/Xx75eDf.jpg"/>
</center>

After developing the Praxis application, our team decided to publish a web demo that architects could use in the early stages of the architectural design process. Although we were going to use the same pix2pix model architecture for this demo, one core feature of this demo was to enable interpolating between different generated outputs.

Whereas generative models that support interpolation in the latent space such as StyleGAN and BigGAN use samples from a noise distribution as input, the pix2pix model architecture takes in images (black-and-white sketches in our case) as input. This difference makes the distribution of the valid inputs much more sparse, making the results of interpolating latent codes in pix2pix models not as good as these models.

In an effort to solve this problem, I conducted research for about two months by doing experiments like adding a new generalization term to the loss that measures the coherence and fidelity of interpolated results, but the research wasn't successful.

We moved forward with what we had, despite the failure of the research. To make it easier for the web developer to interface the trained model to the demo, I created a JavaScript library that loads, generates samples, and interpolates samples using the trained model.

<br>

<!-- Miscellaneous (e.g. Awards & Links) -->
#### Links

**[Link to the website](http://prxs.ai/)**