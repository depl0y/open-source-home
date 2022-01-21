---
title: "Car Chargers"
draft: false
date: 2022-01-11T00:00:00
---

# Car chargers

### Why
- In the end both cars will be replaced with electric cars
- Charging cars with solar panels makes sure we have zero output while driving the car

### Description
As we are slowly transitioning from ICE to electric cars. While it is smart to be prepared for that, it might not be needed to install two chargers immediately.

Currently I am using a [Besen Wallbox](https://www.besen-group.com/ev-charging-station/ev-charging-station-wall/1-3-phase-ev-charging-station-app-control.html) charger which can be monitored and controlled from an app.

For Home Assistant to be able to control it, I need to figure out the network commands it is sending, so I sent a request to the company that created it, to see if any API documentation is available.

### Limitations
When charging a car from home you are limited by your [breaker size](/docs/references/breaker-size/) and of course the maximum capacity of your charger itself.

In the cost calculation below we are using a 3x35A connection, so we can charge cars with a maximum of 22kW.

### Cost
<div class='price-table'>
{{< partial file="/partials/prices/_car-chargers.md" markdown="true" >}}
</div>

### Power usage
<div class="simple-value-table">

{{< partial file="/partials/power-usage/_cars.md" markdown="true" >}}
</div>

> **Attention**  
This is only when all miles are driven using electric. Too bad this isn't the case as you can see in the summary below. For Car 2 (which isn't electric yet) this could be almost 100% electric though.

### Open questions
- [ ] Is this charger the right choice?
- [ ] How do we communicate with the charger?
- [ ] Do we need authentication at the charger? (e.g. with NFC)