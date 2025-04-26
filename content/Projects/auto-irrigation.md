---
title: "Automated Irrigation Project with IoT"
draft: false
summary_template: "summary-with-image"
featured_image: "/images/FF/proj.jpg" 
---

While working on the Field and Fork Farms, I wanted to use my technical background to create a system that would make tasks on the farms easier, one of them being managing irrigation. Currently on the farm, irrigation is semi-manual, by setting timers in person on the farm that controls a schedule for the irrigation. 

<a href="/portfolio/files/Project-proposal-updated.pdf" target="_blank">Read our project proposal here!</a>

The premise of this project is to use capacitive soil moisture sensors to determine when it is best to water the fields. Using measures of moisture, temperature, and light, we want to use this data to turn on and off a solenoid valve, and send all this data to an online dashboard where data can be monitored and valves can be controlled. With remote irrigation, no one needs to be on the farm to monitor the irrigation, and no one will have to manually turn it off during times of heavy rain or wet periods.

{{< figure src="/portfolio/images/FF/proj.jpg" >}}
This is what our current software architecture looks like, and what we want to move towards continuing this project.

{{< figure src="/portfolio/images/FF/current.png" >}}
{{< figure src="/portfolio/images/FF/future.png" >}}

Here's some of the hardware we've been testing with. I want to eventually move all the componenets to a perf board, then design it in KiCad and have it all integrated into one board. 
{{< figure src="/portfolio/images/FF/mc.jpg" >}}

{{< figure src="/portfolio/images/FF/Solenoid_Controller_bb.png" >}}
{{< figure src="/portfolio/images/FF/moisture_sensor_bb.png" >}}

Here's a look at some of the data we've collected and dashboards we've made
{{< figure src="/portfolio/images/FF/charts.png" >}}

{{< figure src="/portfolio/images/FF/adafruit.png" >}}
{{< figure src="/portfolio/images/FF/thingsboard.png" >}}
{{< figure src="/portfolio/images/FF/things.png" >}}

