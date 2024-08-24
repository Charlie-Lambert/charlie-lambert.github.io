---
layout: page
title: Solar Data Logging
description: data logging and interface for off grid cabin
img: assets/img/cabin_gui_electronics.jpg
importance: 3
category: Ongoing
giscus_comments: false
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

At my family's off-grid cabin, we are looking into adding new electrical loads. To better understand our capacity and how the weather affects it, I have installed a Raspberry Pi Compute Module that communicates with our charger and inverter via Ethernet (Figure 1). It collects data and then graphs that data on a display. This project is a work in progress, and I am currently designing the GUI for the display to show the data and help us decide which loads we can or cannot handle.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cabin_gui_electronics.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: data acquisition electronics
</div>
