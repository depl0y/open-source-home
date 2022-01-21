---
title: "Network"
draft: false
date: 2022-01-11T00:00:00
---

# Network

### Why
- Your ISP usually sends you network equipment not ready for this sort of installs
- Full control over network configuration
- Presence detection

### Description
Currently I am using only [Ubiquiti](https://www.ui.com/) gear in my home network.

My current setup contains:
- [Unifi Secure Gateway](https://www.ui.com/unifi-routing/usg/)
- 4x [Unifi AC-PRO Access Point](https://www.ui.com/unifi/unifi-ap-ac-pro/)
- 2x [Unifi Switch Flex Mini](https://store.ui.com/collections/unifi-network-switching/products/usw-flex-mini)

For my future plans I want all ethernet connections to be routed back to the [Utility room](/docs/plans/utility-room). There a bigger switch will be needed to connect everything. As all the access points will also be routed there, the switch could contain a PoE system, so we can phase out all the PoE adapters we currently have (4x for AP, 2x for the small switches).

#### Presence detection
Presence detection is a big part of automating a home. Ubiquity is supported by Home Assistant and we can actually see who is home or not (based on phones connected to the wifi network).

This will allow us to make choices on what to do
- Should lights be turned on/off?
- What about heating / cooling?

![Presence detection](/images/graphs/home.png)

