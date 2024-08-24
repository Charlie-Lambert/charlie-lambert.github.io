---
layout: page
title: Robotic Arm
description: 3D printed robotic arm
img: assets/img/arm_electronics.jpg
importance: 2
category: Ongoing
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

First off, who doesn't want a robotic arm? In all seriousness, 3D printers have significant potential for automation. Tasks like unloading prints, loading prints, placing inserts, magnets, and weights are all potential use cases.

I have extensive experience operating robotic systems using pre-written libraries, but for this project, I plan to take the long road to learn how to write libraries and develop the hardware from scratch. This project is very much a work in progress.

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

So far, I have been developing control systems for the actuators that will be used on the arm. I designed a test fixture that holds a Nema 17 stepper motor with an absolute encoder mounted on the back (Figure 1). I have also written a library that can perform position control and am currently working on torque control.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/arm_actuator.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: actuator testbed.
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

To run the actuator testbed, an electronics testbed was needed. We are currently using a computer power supply, microstep stepper motor controllers, and a microcontroller mounted on a laser-cut piece of wood (Figure 2).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/arm_electronics.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: electronics testbed.
</div>