---
layout: page
title: Battery Rack
description: battery rack for offgrid solar system
img: assets/img/battery_rack_install_crop.jpg
importance: 1
category: Finished
giscus_comments: false
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

I have been working with my family on installing an offgrid solar system at our cabin. Batteries are a vital part of the system.  There are two 24 volt strings of 6 volt L16 units which weigh 1,000 pounds. 

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

In SolidWorks I drafted a 3D sketch of where I would need structural members. This stand is really important because the floor of our cabin typically floods, and the batteries need to be spaced apart (Figure 2).  I then used the weldments feature to insert different geometries of steel for each member (Figure 1). I chose between square tube, C channel, and angle iron. I did a static simulation using Finite Element Analysis (FEA) to understand where the highest loads were (Figure 3).  After establishing those locations, I edited my steel geometries to optimize strength and cost. 

<div class="row justify-content-center">
    <div class="col-sm-6 text-center">
        <figure class="figure">
            {% include figure.liquid loading="eager" path="assets/img/battery_rack_render_iso.jpg" title="Image 1" class="img-fluid rounded z-depth-1" %}
            <div class="caption">Figure 1: battery rack render (ISO view)</div>
        </figure>
    </div>
    <div class="col-sm-6 text-center">
        <figure class="figure">
            {% include figure.liquid loading="eager" path="assets/img/battery_rack_render_side.jpg" title="Image 2" class="img-fluid rounded z-depth-1" %}
            <div class="caption">Figure 2: battery rack render (Side view)</div>
        </figure>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/battery_rack_fea.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 3: FEA
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

I am a self taught MIG welder who has previously done low scale projects such as tables, hooks, and small sheet metal projects. The battery rack was a lot of welding, but my brother and I were able to finish it in 3 days. We fabricated the rack at our house, and then transported the behemoth to our cabin. To prevent rusting, we coated it with a rust preventing primer. The installed rack is fully wired up and the system is functional (figure 4).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/battery_rack_install.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 4: installed rack
</div>
