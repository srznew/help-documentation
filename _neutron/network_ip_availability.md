---
layout: page
title: How Can I Check My Network IP Availability?
featured: false
weight: 3
tags: [neutron, IP, availability]
dateAdded: July 7, 2016
author: Leslie Lundquist
---

## How Can I Check My Network IP Availability?

Many customers have asked how they can check to see how many Floating IPs are left in their availability pool. There’s now an API call and a client call for resource allocation reporting:

```
$ network-ip-availability-list
```
This command gives information about how many floating IPs are used, and how many are still available, of these “consumables.”


