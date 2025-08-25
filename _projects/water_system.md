---
layout: page
title: Water System
description: off grid clean and grey water system
img: assets/img/water_system_1.jpg #thumbnail image path
importance: 4
category: Finished #should either be Ongoing or Finished
related_publications: false
---

<div class="row">
    <div class="col-12">
        <h5><strong>Background</strong></h5>
    </div>
</div>

My family's off-grid cabin is very off-grid. It has no electricity, running water, and dare I say cell service. Each time we make our way up there, we fill up a series of large bottles that will be our drinking water for the week. Whenever we wash dishes, we fill up a bag of water, boil it, and add bleach to ensure it is clean. While I love getting a workout carrying water everywhere, it is definitely a problem that needs to be solved. After installing solar panels and an electrical system, we are finally ready to take on the project.

<div class="row">
    <div class="col-12">
        <h5><strong>Design</strong></h5>
    </div>
</div>

Water systems have two sides: clean and grey. The clean water system describes the sourcing, cleaning, and distributing the water to faucets and a shower. The grey water system describes how used water is collected and treated. Both systems will be described in this project.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/water_system_0.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: clean water system
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/well_pump.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2: well pump hanging bracket and electrical connection
</div>

The main goal for the clean system, shown in Figure 1, is to collect, filter, and provide water to faucets. Water is pumped out of a well using a submersible pump, shown in Figure 2, that hangs from the top of the well and dangles near the bottom. At this point, large particles are filtered out of the water to make sure large amounts of dirt, silt, or other large contaminants do not make it into our storage tank. The water rests in a 100-gallon storage tank that uses a float sensor to detect if it is full and turn the pump on and off. Using this float switch, the frequency at which water is pulled from the well can be set, which is important since the well needs time to replenish. This water is sitting on the first floor in a tank and needs to be distributed to the rest of the cabin. A pressure pump and pressurized tank accomplish this. Large pressurized tanks are expensive and hard to clean. For these reasons, we have a smaller pressurized tank and a pump that works to pressurize it to 25 gallons for the tank size. To pressurize our tank, water flows out of our large storage tank and gets pumped by a high-pressure pump. We learned the hard way that pressure relief valves were needed when a water filter cracked and exploded after a valve was accidentally closed. Before it reaches the pressurized tank, the water makes it through smaller and smaller filters, then a UV filter, and finally one last fine particulate filter. These filters remove the last small particulates, kill any bacteria in the water that could be harmful, and then remove the bacteria. This pressurized water now can flow into the two faucets and one shower. All of these pumps and the UV filter operate on the solar electrical system that powers our cabin in another project I designed and welded a battery rack for that system.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/water_heater.JPG" title="example image" class="img-fluid rounded z-depth-1" style="transform: rotate(90deg)" %}
    </div>
</div>
<div class="caption">
    Figure 3: wall mounted water heater and bathroom sink
</div>

Running water itself is game-changing in an off-grid cabin, but once you have water, adding hot water isn’t that much more work. The cabin already has propane, so we installed a propane instant hot water heater shown in Figure 3. One major issue is that it can take a while for some of the water to get to temperature, so we installed a circulation loop. The circulation loop circulates water through the heater, turning it on and getting up to temperature before water is needed, so if you want a hot shower, you gotta turn the timer on the circulation pump on for 5 minutes before you shower. This ensures that we aren’t wasting gallons of water waiting for the shower to heat up, but rather the water is hot when the faucet is turned on.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/grey_water_2.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 4: cast iron pipes guiding water to grey water tank
</div>

Once water has been used in the sinks or shower, it is now considered grey water. Underneath the cabin sits a storage tank where this water is collected and then can be correctly disposed of. Installing pipes, shown in Figure 4, and hanging them underneath a cabin next to a swamp is not exactly the most fun activity. To reduce the time spent under there measuring and cutting, I took measurements of the locations of the drains, tank, and floor beams. With these measurements, I drafted a CAD model and assembled the pipes digitally to get a bill of materials and pipe lengths that we could use during fabrication.

<div class="row">
    <div class="col-12">
        <h5><strong>Fabrication</strong></h5>
    </div>
</div>

There is a lot of hardware that needed to be built and installed for these systems to operate. A large amount of welding was done to fixture filters, pipes, pumps, tanks, and gauges for our filtering system. The submersible well pump hangs from a welded fixture made from scrap steel. The pipes the water flows in throughout the cabin are copper pipes that have been sweated together using an acetylene torch. My dad learned this as a kid and has passed the skill down to my brother and me. Inside the cabin, we didn’t want to open up a lot of walls, so all of the pipes are run out in the open, which I think looks really cool. To add flare to the pipes and hold them in place, I cut holders for them on a CNC router. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bathroom_sink_crop.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 5: custom backsplash for the bathroom sink
</div>

To hold the pipes and faucets for sinks using come off cuts from a log a neighbor provided, I designed cutouts for the pipes and faucet parts, which I routed away on a CNC router. The parts, shown installed in Figure 5 were further finished with varnish to prevent the pipe condensation and splashing from the sink to get into the wood.

For the grey water system, pipes are run outside of the cabin and are hung from the floor joists. All of the pipe is cast iron, so there is little to no risk of it ever cracking in the event that water freezes inside of it during the winter. Aside from the pipes, a large greywater tank was installed to collect all of our grey water. To ensure the tank doesn’t float away, a large slab of concrete was poured to weigh it down.
