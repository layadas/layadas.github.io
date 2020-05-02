---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My work focuses on ***understanding, monitoring and controlling complex systems*** by merging domain knowledge and information extracted from data. In the engineering fields,
these complex systems are typically ***cyber-physical systems*** such as smart grid, transportation network and industrial control systems. I work on problems at the
intersection of theory and applications.

<!-- You can find details 

{% include base_path %}

{% for post in site.research/ reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Ongoing Projects

### Resilience of Smart Grid
The smart grid is prone to extreme conditions imposed by the environment such as hurricanes and cyber-attacks that can result in loss of power. A resilient grid swiftly recovers
from such conditions and resumes normal operation. I am currently working on quantifying the resilience of smart grid with graph theoretic methods.
- This project is in collaboration with [Dr Babji Srinivasan](https://www.iitgn.ac.in/faculty/chemical/fac-babji) and
[Prof Balasubramaniam Natarajan](http://www.ece.k-state.edu/people/faculty/natarajan/)

### Equilibrium Dynamics of Systems with Competing Phenomena
Systems with large number of agents are known exhibit self-organization, i.e., emergence of order and patterns in the absence of a leader. Self-organization is observed in a wide
range of
systems, including uniform distribution of gas molecules in a room to formation of termite
mounds. We present a unifying framework that is capable of (i) capturing the general
behaviour of self-organizing systems, as well as (ii) incorporating the nuances of different
systems with appropriate modifications. The proposed framework adopts a utilitarian
approach – one where an individual agent tries to maximize its utility and self-organization is
achieved as a result of collective evolution of interacting agents. We show that such an
approach inherently introduces the concept of entropy maximization and different constraints
imposed on the system (and agents) result in different distributions characterizing the self-
organizing patterns. Furthermore, the framework handles the presence of multiple
populations of the agents – compatible or incompatible – with the concept of cross-entropy,
and generalizes well to systems with any number of competing populations. While the
individual agent in the system attempts to maximize its utility, equilibrium of the system as a
whole is shown to be achieved through maximization of entropy and cross-entropy. The
framework is observed to be capable of accurately predicting the behaviour of passive (gas
molecules, oil-water mixture) as well as active matter (termite mounds) and propounds
entropy (and cross-entropy) as the underlying phenomenon driving self-organization.

## Past Projects

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