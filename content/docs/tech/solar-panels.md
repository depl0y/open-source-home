---
title: "Solar Panels"
draft: false
date: 2022-01-11T00:00:00
---

# Solar panels

### Why
- We want to generate AT least as much energy as we plan to use
- Very environment friendly
- Air conditioning and ground source heat pumps use a lot of energy


### Description
Solar panels, the aren't many reasons to not use them. The investment up-front could be one of them, so it would be good to check how we can make the system extensible.

Because this tech is outdated as soon as you write it down, we are checking the current (2022) offerings and see how it work *now*.

| Calculation | Values | Unit |
| - | -: | :- |
| Predicted yearly usage | 12.000 | kWh |
| Panel production | 385 | Wp |
| Amount needed | 32 | panels |

In this calculation we need at least 32 panels to fulfil our energy usage. We need a very detailed calculation for this, to see what the *predicted yearly usage* is.

### Open questions

- [ ] How much energy is expected to be used by the car?
- [ ] What type of converter is needed to accommodate this many solar panels?
- [ ] Is there a way to increase efficiency when temperatures are really high?
- [ ] What is the breaker capacity we need for this?
- [ ] Do we need [energy storage](/docs/tech/energy-storage) when we produce more power than we use?

I found this table somewhere for reference, this needs to be checked when ordering:

| Power connection | Max breaker | Max capacity |
| :- | -: | -: |
|1 x 25A|16A|3.680 Watt|
|1 x 35A|25A|5.750 Watt|
|1 x 40A|25A|5.750 Watt|
|3 x 25A|3 x 16A|3 x 3.680 Watt|
|3 x 35A|3 x 25A|3 x 5.750 Watt|
|3 x 40A|3 x 32A|3 x 7.360 Watt|
|3 x 63A|3 x 40A|3 x 9.200 Watt|
|3 x 80A|3 x 50A|3 x 11.500 Watt|