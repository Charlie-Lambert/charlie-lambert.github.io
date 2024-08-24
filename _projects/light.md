---
layout: page
title: Light Fixtures
description: custom DC lights
img: assets/img/light_cartridge_metal_crop.jpg #thumbnail image path 
importance: 1
category: Finished #should either be Ongoing or Finished
related_publications: false
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

At my family's off-grid cabin, we had numerous propane appliances: lights, refrigerator, stove, and heater. All of these produce carbon dioxide and trace amounts of carbon monoxide inside the cabin. To reduce the production of these gases, we made an effort to replace the propane lights with electric ones. I took on the project of designing light fixtures that could be placed throughout the cabin.

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

The electronics are powered by a solar system we recently installed to support our water system and other appliances within the cabin. Our batteries supply 24 volts of DC current that powers the entire cabin. To prevent issues with voltage drop over the long wires running to the light fixtures, each fixture operates on 12 volts. A buck converter is placed in front of a strip of LEDs that produce the light. To replicate the feel of the gas fixtures, I chose a similar color of light. After experimenting in similarly sized dark rooms, I determined that around 1800 lumens would be needed.

With the electronics chosen, the next step was to design a fixture to hold them. I went through several design iterations to house all the LEDs and electronics (Figure 1). My initial idea was to have two rings of LEDs—one on the outside and one on the inside. The inner LEDs would have a reflector and diffuser to direct light downward. However, this design proved ineffective in reflecting light downward. Using aluminum foil-backed adhesive, a 3D printer, and a laser cutter, I was able to rapidly prototype new designs.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_proto.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: cartridge prototypes
</div>

After deciding to place the LEDs facing directly downward, I made significant progress with the fixture. However, the new design required a lot of manual wiring between each strip (Figure 2). To streamline the process, I designed a printed circuit board (PCB) to route power (Figure 3).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_wires.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: cartridge prototype wiring
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_pcb.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 3: PCB
</div>

With the light source design complete, I focused on the surrounding hardware. We found decorative brass hardware on vintage lighting websites to mount the fixtures.

Once the first versions of the fixtures were installed, they were tested in place for about a year. Over time, they exhibited a major issue: warping. The plastic parts heated up and began to warp and shift (Figure 4). To resolve this, I redesigned the 3D-printed parts to be machined out of aluminum, ensuring that the heat from the LEDs would be dissipated and the fixtures would remain stable.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_cartridge_plastic_crop.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 4: plastic warping
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

With the addition of aluminum parts, fabrication became more complex. Lacking access to the necessary machines, we outsourced the machining (Figure 5). The other parts were 3D-printed and laser-cut to complete the fixtures. Once all the parts were in hand, I assembled the light fixture cartridges (Figure 6).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_metal.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 5: machined cartridge
</div> 

 <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_cartridge_metal_crop.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 6: cartridge
</div>

The brass parts fit perfectly with the cabin's style, and the lights have proven to be a great replacement for the previous gas fixtures (Figures 7 and 8).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_cabin_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 7: dual cartridge fixture
</div> 

 <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/light_cabin_2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 8: single cartridge fixture
</div>