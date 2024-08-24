---
layout: page
title: FERDA-L1
description: regeneratively cooled liquid rocket engine
img: assets/img/ferda_front.jpg
importance: 1
category: Ongoing
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

For the past two years, I have been working with a team of six other undergraduate students to develop a regeneratively cooled liquid rocket engine. The goal of this project is to build and test Harvey Mudd College’s first-ever liquid rocket engine with regenerative cooling.

We set the following design goals to create a baseline for the first iteration of our engine: use gaseous oxygen and kerosene as propellants, and use kerosene to regeneratively cool our engine. This engine was not designed to fly on a rocket but instead to help us learn about designing, manufacturing, and testing engines.

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

FERDA-L1 will be designed for static firing to understand how analysis models compare with the physical system. Later iterations of the engine will eventually be used on a rocket in college-level rocketry competitions. These competitions generally involve class 3 rockets, which require a total impulse of 1151-9,206 lbf•s (M-O motor classification). For the first iteration, the design will likely be on the lower end of this impulse class.

A gaseous-oxygen (GOX) and kerosene engine has an optimal mixture ratio (oxidizer/fuel: O/F) of 2.3 at a chamber pressure of 500 psig. To lower the required propellant flow rate and adiabatic flame temperature, we are using a lower O/F ratio of 2.15. This ratio can be adjusted in later iterations to increase efficiency. We have also chosen a thrust of 800 lbf. The chamber pressure and thrust were somewhat arbitrary design choices but were selected to ensure that the resulting calculations are reasonable.

Later calculations were used to determine engine geometry, thermal loads, structural loads, and fuel flow rates. Please feel free to contact me if you are interested in learning more about the design!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ferda_diag.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: engine diagram
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

I am responsible for manufacturing the engine and test stand components. Most engine and test stand components were machined in our student shop. Our chamber and saddle components required some fixturing that we did not have in-house, so we sent them out to be machined (Figure 1). Most regeneratively cooled engines today are 3D printed or plated; however, in hopes of manufacturing all components in our student shop, we chose to use a saddle and outer jacket. We manufactured our parts using both 3-axis and 5-axis CNC machines and programmed them using Fusion360 (Figure 2).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ferda_cam.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: injector CAM
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Testing</strong></h5>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ferda_test_stand.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 3: test stand at test site
</div>

I am responsible for developing the testing infrastructure for our engine. To supply our oxidizer and fuel, a high-pressure plumbing system was designed and built. Both high-pressure gases and oxidizers are extremely dangerous, so burst disks, pressure relief valves, and remotely controlled valves were implemented to ensure the system could be manually loaded and remotely operated. The test stand was built and tested at low and high pressures on campus with inert gases before being transported to Friends of Amateur Rocketry (FAR), where we attempted a static fire (Figure 3 and 4). Last May, we attempted to static fire our engine but faced ignition and control issues. We will be working this fall to address these issues and achieve ignition!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ferda_front.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 4: engine mounted on stand at test site
</div>
