---
layout: page
title: The use of gliders in the coastal zone
description: This project developed during my PhD consisted on the use of gliders to study the hydro-sedimentology of the Gulf of Lions during extreme events, such as flood of the Rhône River and storm. Here, an introduction to ocean gliders is presented, and a focus is made on the main results we obtained using such innovative measurement platforms.
img: assets/img/proj1/glider.gif
importance: 1
category: work
---

<h2> Introduction to ocean gliders </h2>

<a href="https://www.researchgate.net/publication/265913484_Gliders_as_a_Component_of_Future_Observing_Systems">Ocean gliders</a> are increasingly used in ocean observations. These Autonomous Underwater Vehicles (AUVs) are self-propelled by a control of their buoyancy, which made them able to move to a specific location and depth. They are equipped with physical and optical sensors to monitor hydrological and biogeochemical processes operating within coastal waters with a high spatial and temporal resolution. They use a variable buoyancy to sink or to rise through the water column. This motion is converted to a sawtooth-shaped trajectory (pitch angle of approx. 25°) by the presence of rigid wings near the center of the vehicle. Gliders are typically equipped with a CTD sensor (Conductivity, Temperature, Depth) as well as miniaturized optical sensors (turbidity, fluorescence). Gliders can be deployed during long periods (> 1 month), long distances (> 50 km) and during energetic events (as storms). They provide a high density of in situ information. The related cost-efficiency of glider observations is very low compared to ship observations, which shows the “middle-cost for a high efficiency” character of gliders.

<div class="row mt-1">    
        {% include figure.html path="assets/img/proj1/glider.gif" class="img-fluid rounded z-depth-1" %}
</div>

<div class="caption">
  The glider is controlled remotely by satellite by the "gliderman". Its irridium connection allows missions to be programmed and data to be collected when the glider communicates while on the surface.
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
