---
title: "Monitoring"
draft: false
date: 2022-01-11T00:00:00
---

# Monitoring

### Why
- It allows predictions.
- To keep an eye on our usage numbers, when is this changing, etc?

### Description
Keeping an eye on the sensors we have in and around the house can tell us a lot. We want to be as energy neutral as we can, so we need to have monitoring with alert values.

#### Example #1
When the outside temperature drops to around 0 degrees, there are a couple of things we need to be mindful of:
- Did we close the taps to our outside faucets?
- Can we adjust the temperature of our heated drinking water?
- Can we pre-heat car-batteries before taking a trip (to be more efficient)?

![Temperature graph](/images/graphs/temperatures.png)

#### Example #2
When the power usage spikes at certain times. There are again a couple of questions we should answer
- What is causing this spike?
- Is this regularly the same spike?
- Is this at an ideal time? For example a dish-washer would best run when solar produces more energy (depends on [energy storage](/docs/tech/energy-storage))

![Temperature graph](/images/graphs/power-usage.png)

### Open questions
- [ ] Where do we store the monitoring data? Currently we are using [InfluxDB](https://www.influxdata.com/) for this.
- [ ] What dashboard do we use?
- [ ] What graphs are useful?
- [ ] Backups?