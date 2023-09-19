---
layout: page
title: 3D Semantic Scene Understanding
description: A performance analysis on applying Large Language Model to enhance semantic 3D scene understanding. This is a course project done with other two students for EECS487 Natural Language Processing in the University of Michigan.
img: assets/img/cover_vis.png
importance: 1
category: research
redirect: /assets/pdf/Leveraging_Large_Language_Models_for_Robot_3D_Scene_Understanding__Final_Report.pdf
---


Robotic applications rely on scene understanding to analyze objects within a 3D environ- ment. One crucial component of scene understanding is semantics labeling, which involves assigning class labels to semantic regions based on the objects within them. A visualization of the semantics labeling process is shown in Figure 1. In a recent study [1], Large Language Models (LLMs) were found to be effective in incorporating common sense knowledge during the labeling process. In this project, we aim to compare two LLMs, GPT-J and RoBERTa, using fine-tuned feed-forward and contrastive networks, which were not evaluated in [1], for the semantic labeling task. The contributions of this project are twofold: (i) The proposed GPT-J with fine-tuned feed-forward network achieves state-of-the-art(SOTA) performance, and (ii) by varying the number of candidate objects, adopting ChatGPT-based room detection and fine-tuning a whole BERT-based network, we explore the possible performance bottleneck of our proposed GPT-J pretrained network.


For more information, please refer to our report and <a href="https://getbootstrap.com/docs/4.4/layout/grid/">codebase</a>

For more information, please refer to our [report](/Users/jimmyyu/Desktop/jimmyyu-folio.github.io/assets/pdf/Leveraging_Large_Language_Models_for_Robot_3D_Scene_Understanding__Final_Report.pdf) and [codebase](https://github.com/XihangYU630/llm_scene_understanding_gptj).



[1] William Chen, Siyi Hu, Rajat Talak, and Luca Carlone. Leveraging large language models for robot 3d scene understanding. arXiv preprint arXiv:2209.05629, 2022.

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
