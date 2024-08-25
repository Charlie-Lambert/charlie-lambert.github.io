---
layout: page
title: Lantern
description: custom and rechargeable light source
img: assets/img/lantern_action.jpg
importance: 6
category: Finished
related_publications: false
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

I came across quite a few 18650 lithium ion batteries and some Cree XHP70 LEDs which produce 4000 lumens—a lot of light. I took the opportunity to produce a fully fledged product that would be easy to use, powerful, and have a long battery life.

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

With those goals in mind, I started with the electronics. I created a 4 cell 4.2 volt battery pack. I rigged up a USB charging circuit that charges the packs. The LED runs at 6 volts, so I step up the voltage to 6 volts with a buck converter. This setup allows the LED to run for 2 hours at full brightness, and 3+ hours at a lower brightness. 

The batteries and charging components are stored in the bottom half, while the step up, switch and dimming circuit are stored in the top. Two threaded rods take power from the bottom to the top. A noticeable difference between the render and photo show the addition of a diffuser on the light which makes the operation a lot more pleasant (Figure 2). After learning about conics in my math class, I added a conical reflector beneath the LED to help disperse the light.

All of the parts were designed in OnShape. SolidWorks was used to produce renders of the model.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lantern_render.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: render of lantern model.
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

Almost all of the parts are 3D printed with thread inserts, and the rest are cut out of either ABS or PVC plastic on a CNC router. I used Vcarve to CAM all of the parts that were cut on a CNC router.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lantern_build.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: fabricated lantern
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lantern_action.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 3: lantern in action
</div>