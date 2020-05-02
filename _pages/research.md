---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My work focuses on ***understanding, monitoring and controlling complex systems*** by merging domain knowledge and information extracted from data. In the engineering fields,
these complex systems are typically ***cyber-physical systems*** such as smart grid, transportation network and industrial control systems. I work on problems at the
intersection of theory and applications.

You can find details about the ongoing and completed projects below.

<!-- 
{% include base_path %}

{% for post in site.research/ reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Ongoing Projects

### Resilience of Smart Grid (2019-Present)
The smart grid is prone to extreme conditions imposed by the environment such as hurricanes and cyber-attacks that can result in loss of power. A resilient grid swiftly recovers
from such conditions and resumes normal operation.
- This project is in collaboration with [Dr Babji Srinivasan](https://www.iitgn.ac.in/faculty/chemical/fac-babji) (IITGN) and
[Prof Balasubramaniam Natarajan](http://www.ece.k-state.edu/people/faculty/natarajan/) (KSU)
- We have submitted a review of the methods, challenges and opportunities in measuring resilience of smart grids.
- We are currently working on quantifying the resilience of smart grid with graph theoretic methods. We plan to exploit graph theoretic properties of networks along with physical
information about grid parameters to quantify resilience to extreme events.

### Equilibrium Dynamics of Complex Systems with Competing Phenomena (2020-Present)
Several of modern man-made systems are complex enough to challenge the minds of their designers. This project is aimed at understanding the dynamics of systems with several
interacting units at equilibrium so that they can be better modelled, monitored and controlled. Applications of such an anlysis can be found in robotics and drone-assmebly control.
- This project is a part of my post-doc research with [Prof Venkat Venkatasubramanian](https://datascience.columbia.edu/venkat-venkatasubramanian-0) (CU).
- We are working on developing a framework that captures the dynamics of individual units and accounts for their interactions, that can identify the equilibrium of such systems.

## Completed Projects

### Performance Assessment of Estimation and Control in Industrial Cyber-Physical Systems
Industrial plants that manufacture say, steel or electronic chips contain thousands of control loops. These control loops typically depend on state estimation for calculating the
control moves. It is imperative the control loops perform as desired to ensure the quality of product. My PhD thesis was targeted at quantifying the performance of state estimation
and control in a manufacturing plant/unit, with several variables interacting with each other.
- In order to make the approach independent of confounding factors, I employed predictability as a measure of performance
- In order to account for interactions between the different variables, I proposed the Mahalanobis distance for developing a single performance metric of the systems
- In order to automate the approach, I employed a data mining approach to extract prior knowledge about the system from data

### Data Management in Smart Grid
In a smart grid, power consumption data is collected at consuming nodes and communicated to data processing centres for analysis. A back-of-the-hand calculation revleas that sizable
city like Chennai can generate 3 TB of data in as much time as a day to a fortnight, depending on the sampling rate, and communicating and storing such data is a challenging affair. I
worked collaboratively on compressing this data to a mangeable volume with signal processing and machine learning.
- In order to account for temporally varying properties of power consumption data, we proposed a dynamic compressed sensing approach for data compression
- In order to account for locality-based similarities in consumption patterns, we proposed PCA along with compressed sensing to perform spatio-temporal compression
- In order to improve the compression ratio, I employed autoencoders to perform nonlinear compression of the consumption data


### Additional Projects
I have been involved in a few additional projects during PhD and post-doc:
- Understanding control room operator actions with cognitive engineering (IITGN)
- Sensor placement for leak localisation in water distribution networks (IITGN)
- Fault diagnosis of DC motors with machine learning (IITGN)
- Understanding the hidden representations of neural networks (CU)
- Developing a framework for explaining pattern formation in complex systems (CU)