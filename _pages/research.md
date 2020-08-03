---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My work focuses on ***understanding, monitoring and controlling complex systems*** by merging domain knowledge and information extracted from data. In the engineering fields,
these complex systems are typically ***cyber-physical systems*** such as smart grid, transportation network and industrial control systems. I work on exciting problems at the
intersection of theory and applications.

I have had the opportunity to work in multi-discplinary teams, with members from Electrical Engineering, Chemical Engineering, Computer Science and Physics. You can find details
about the ongoing and completed projects below.

<!-- 
{% include base_path %}

{% for post in site.research/ reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Ongoing Projects

### Fault Detection of Wind Turbines (2020-Present)
Wind turbines are an important renewable energy generators that harness the energy from wind. Wind turbines, like all devices are prone to faults that result in poor performance,
and at times loss of power. Fault detection of wind turbines is typicaally carried out with vibration data - an exhaustive set of measurements from tens or hundreds of (extremely
expensive) sensors.
- This project is in collaboration with [AspenTech](https://www.aspentech.com/) under the
[AspenTech Academy](https://www.aspentech.com/en/resources/press-releases/aspentech-announces-aspentech-academy15032387419) program.
- We are exploring techniques for detecting faults in wind turbines with SCADA data - that is easily available.
- Raw measurements and derived variables are used to identify patterns indicative of abnormal behaviour using stastical techniques.

### Resilience of Smart Grid (2019-Present)
The smart grid is prone to extreme conditions imposed by the environment such as hurricanes and cyber-attacks that can result in loss of power. A resilient grid swiftly recovers
from such conditions and resumes normal operation.
- This project is in collaboration with [Dr Babji Srinivasan](https://www.iitgn.ac.in/faculty/chemical/fac-babji) (IITGN) and
[Prof Balasubramaniam Natarajan](http://www.ece.k-state.edu/people/faculty/natarajan/) (KSU).
- We have submitted a review of the methods, challenges and opportunities in measuring resilience of smart grids.
- We are currently working on quantifying the resilience of smart grid with graph theoretic methods. We plan to exploit graph theoretic properties of networks along with physical
information about grid parameters to quantify resilience to extreme events.

### Formation Control Problems in Natural and Man-made Systems (2020-Present)
The complexity of modern man-made systems is beginning to challenge the minds of their designers. This project is aimed at understanding the dynamics of systems with numerous
interacting units at equilibrium so that they can be better modelled, monitored and controlled. Applications of such an anlysis can be found in control of robots and drone ensembles.
- This project is a part of my post-doctoral research with [Prof Venkat Venkatasubramanian](https://datascience.columbia.edu/venkat-venkatasubramanian-0) (CU).
- We are working on developing a framework that captures the dynamics of individual units and accounts for their interactions towards identifying the equilibrium of such systems.

<!-- ### Understanding Neural Networks
 -->
## Completed Projects

### Performance Assessment of Estimation and Control in Industrial Cyber-Physical Systems
Industrial plants that manufacture say, steel or electronic chips contain thousands of control loops, that typically depend on state estimation for calculating control moves. The
performance of these control loops determine the quality of the product (steel/chips). This project was aimed at quantifying the performance of state estimation and control in a
manufacturing plant/unit, with several variables interacting with each other.
- This project was my PhD thesis (titled *Assessing the Performance of Estimation and Control: from Data to Knowledge*) with
[Dr Babji Srinivasan](https://www.iitgn.ac.in/faculty/chemical/fac-babji) at IITGN
- During my PhD, I was deputed to IIT Madras as a visiting student, where I closely worked with [Prof Raghunathan Rengaswamy](https://che.iitm.ac.in/?page_id=380) on my thesis.
- The developed approach exploited the interplay betwen performance, predictability and correlations between variables in control loops.
- The framework was tested on simulated systems, experimental setups and real life industrial data.

### Data Management in Smart Grid
In a smart grid, power consumption data is collected at consuming nodes and communicated to data processing centres for analysis. A back-of-the-hand calculation revleas that a
sizable city like Chennai can generate 3 TB of data in as much time as a day to a fortnight, depending on the sampling rate, and communicating and storing such data is a challenging
affair. This project was aimed at reducing the size of data to a mangeable volume with signal processing and machine learning.
- This project was in collaboration with [Dr Babji Srinivasan](https://www.iitgn.ac.in/faculty/chemical/fac-babji) (IITGN), 
[Prof Balasubramaniam Natarajan](http://www.ece.k-state.edu/people/faculty/natarajan/) (KSU) and
[Dr Dinesh Garg](https://researcher.watson.ibm.com/researcher/view.php?person=in-garg.dinesh) (then at IITGN).
- A novel metric-based dynamic compressed sensing along with principal component analysis was employed to perform spatio-temporal compression of power consumption data
- The compression ratio was improved by performing nonlinear compression with autoencoders.

### Additional Projects
I have been involved in a few additional projects:
- **Understanding control room operator actions with cognitive engineering (2017-2018, IITGN)**: This project was in collaboration with
[Prof Rajagopalan Srinivasan](https://che.iitm.ac.in/?page_id=457) (then at IITGN), where we employed eye tracking to understand the behaviour of control room operators in industrial
plants
- **Sensor placement for leak localisation in water distribution networks (2018, IITGN)**: This was a project funded by the WIN foundation with the objective of identifying sensor
locations for leak localisation in water distribution networks.
- **Fault diagnosis of DC motors with machine learning (2018, IITGN)**: I worked with a Masters' student to employ machine learning for diagnosis of incipient faults in DC motors.