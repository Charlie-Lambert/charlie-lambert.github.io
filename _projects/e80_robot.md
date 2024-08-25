---
layout: page
title: Autonomous Underwater Vehicle
description: seafloor and temperature mapping robot
img: assets/img/e80_robot_bottom.jpg #thumbnail image path
importance: 2
category: Finished #should either be Ongoing or Finished
related_publications: false
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

In the spring of 2024, I took Harvey Mudd College's (HMC) E80 Experimental Engineering course. This course is known as one of HMC’s most challenging, offering extensive hands-on experience in analog electronics, simulation, wind tunnels, and control systems. For the final project, teams of four students design, fabricate, code, and test an autonomous underwater vehicle (AUV) to perform an experiment in the Pacific Ocean. My team chose to build a robot that would map the depth and temperature of the ocean, specifically focusing on Dana Point, our testing location.

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

To achieve our goal, we selected a pressure transducer to measure depth, a thermistor to measure temperature, and an array of switches to detect the ocean floor. We then designed the supporting analog and digital circuitry to optimally scale our analog sensor outputs for our microcontroller and to isolate impedances. A pressure transducer circuit (Figure 1), a temperature circuit, and a switch circuit (Figure 2) were developed to assist our Teensy microcontroller in collecting accurate data during deployment.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/e80_pressure_circuit.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: pressure transducer circuit
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/e80_switch_circuit.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: switch circuit
</div>

Mechanically, our robot was relatively simple. It was constructed from PVC tubes, a dry box, steel weights, and pool noodles for buoyancy. We used SolidWorks to model the robot and understand the center of gravity, which helped us in the strategic placement of the pool noodles. To mount the switches on the robot, we designed 3D-printed mounts with long fingers to ensure the switches would contact the sea floor before the robot did.

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

After testing all our circuits with breadboards, we soldered the components onto protoboards, which were then wired to our microcontroller. Once all the supporting circuitry was complete, we placed the components inside the dry box.

Mechanically, the project involved a lot of cutting and connecting PVC. The mounting hardware for our switches needed to be 3D printed and securely attached to the robot.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/e80_robot_bottom.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 3: robot bottom
</div>

<div class="row">
    <div class="col-12">
        <h5><strong>Testing</strong></h5>
    </div>
</div>

After assembling the robot, we encountered some troubleshooting challenges that needed to be addressed before everything could function properly. We spent significant time testing and tweaking the robot in HMC's pool. After numerous adjustments, we felt confident that our robot was ready for deployment.

However, in the ocean, our robot faced several issues. Our sensor systems experienced a lot of noise, causing the switches to trip incorrectly and the thermistor circuit to produce inaccurate temperature readings. We hypothesized that the increased buoyancy from the saltwater, coupled with the added weight, made the motors work harder, leading to interference in our sensors. An analog reading of our digital switch pin graphed next to motor power made us believe that increased motor power created interference that caused the digital pin to cross the trigger threshold in sync with the motor power cycle (Figure 4).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/e80_data_noise.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 4: interference plot
</div>

Despite these challenges, our team was able to modify our procedure and gather depth measurements at different GPS locations, which allowed us to create a proof-of-concept 3D map (Figure 5). With additional time, we could have collected more data points to create a more extensive map.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/e80_data_depth_3d.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 3: proof of concept map
</div>
