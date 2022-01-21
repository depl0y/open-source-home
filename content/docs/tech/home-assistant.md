---
title: "Home Assistant"
draft: false
date: 2022-01-11T00:00:00
---

# Home Assistant

![Home Assistant logo](/images/home-assistant.png)

### Why
- Open source
- Easy to automate certain tasks, set time limits on lights, etc.
- Ability to add my own integrations when certain hardware isn't supported
- Easy to monitor sensors in the house

### Description
Next to a [home automation](/docs/tech/home-automation) system, I also want to use  to tie stuff together. Currently I use Home Assistant to turn lights on and off based on time of day, light levels in house and certain schedules. Next to that I use it to log data about our current house, like electricity and gas usages.

Because HA is really easy to extend with new modules and the community is really alive, I plan to use it to make certain things work which each other.

Things I see where Home Assistant could be really useful:

- Monitor output of solar panels to see if (for example) a car should be charged.
- Give the car charger a command to actually charge a car.

One of the challenges is to keep the house operating while Home Assistant goes down (or is under maintenance). This is one of the things that really brings down reliability.

#### Overview
Below you see an example of a part of the data that is available through home Assistant.

![Home Assistant example 1](/images/home-assistant-1.png)

### Open questions
- [ ] How to make Home Assistant more resilient?
- [ ] Should we separate Zigbee and Home Assistant to keep light functionality when Home Assistant goes down?
- [ ] How do we create a production and test environment that can be exchanged (e.g. when upgrading) ?
- [ ] Where do we store the [monitoring data](/docs/tech/monitoring)?

### Links

- [Home Assistant website](https://www.home-assistant.io/)
