---
layout: work
title: Projects
slug: /projects
---
## Samara Autorotating Wings (SAW)

The SAW project takes inspiration from the graceful falling of maple seeds, sometimes more fondly known as _helicopter seeds_. The main purpose of SAW platform is for precision aerial deployment of lightweight payloads at a relatively low-cost. It is ideal for applications such as precision reforestation projects, sensor deployments for remote sensing such as detection of natural disasters such as forest fires, flood, or monitoring of wild life, agriculture, gases and chemicals, weather detection and so on. This project has currently been explored in the following five focal points.

### 1. Optimized Wing Planform

![Maple seed and SAWs](https://www.dropbox.com/s/lzkwshrs600lvqu/Cover.jpg?raw=1)

The size and shape of the wing affects how fast the platform rotates, how fast it drops, its pose and coning angle. Therefore, the wing planform of SAW is carefully chosen in order to achieve the slowest drop speed, a decent rotation speed, which also affects the glide slope. The parameters being chosen include wing length and chord length, with a third order polynomial to ensure the shape remains smooth. A flat plate airfoil is used as the size of the platform is relatively small and the airfoil effects are considered minimal. Blade Element Theory is used to model the platform in 6 degrees-of-freedom free-fall scenarios, with various algorithms such as gradient descent and genetic algorithm are used to find the optimum solution. Various optimization methods are discussed in the following papers.

 - [The effect of chordwise wing optimization of single-winged samara in autorotation](https://doi.org/10.1109/AIM.2017.8014118) in _IEEE International Conference on Advanced Intelligent Mechatronics 2017_.
 - [Direction controlled descent of Samara Autorotating Wings (SAW) with n-wings](https://doi.org/10.1109/ICRA.2018.8463145) in _IEEE International Conference on Robotics and Automation_.
 - [Design, modelling and control of collaborative Samara Autorotating Wings (SAW)](https://doi.org/10.1007/s41315-019-00091-6) in _International Journal of Intelligent Robotics and Applications, , Vol 3, 144-157, 2019._
 - [Dynamics and control of a collaborative and separating descent of samara autorotating wings](https://doi.org/10.1109/LRA.2019.2924837) in _IEEE Robotics and Automation Letters, Vol 4(3), 3067-3074, 2019._
 - [An agile samara-inspired single-actuator aerial robot capable of autorotation & diving](https://doi.org/10.1109/TRO.2021.3091275) in _IEEE Transactions on Robotics, Early Access_.

### 2. Collaborative Units and Mid-Air Separation

![Experiment](https://www.dropbox.com/s/ff0ps2mojtno1a7/Experiment.jpg?raw=1)

SAW units can be joined together as a rotor hub, looking rather like a flower. In this configuration, they can collaboratively work together, achieving better resilience as tough wind conditions. At a desired altitude, the units can exit the collaborated form, splitting to individual units and continuing their trajectory towards each respective landing locations. To achieve this, a unique de-centralized separation mechanism is designed, the separation manoeuvre is first simulated and then verified in a special experiment setup. More details can be found in -

 - [Dynamics and control of a collaborative and separating descent of samara autorotating wings](https://doi.org/10.1109/LRA.2019.2924837) in _IEEE Robotics and Automation Letters, Vol 4(3), 3067-3074, 2019._

### 3. Solar-cell Wings

![SolarSAW](https://www.dropbox.com/s/1gh7we69kz39be1/SolarSAW.JPG?raw=1)

Once SAW lands at a designated place, the payload sensor can begin collecting its data. Its service life can be extended indefinitely by integrating solar cells as a multi-functional wing structure. As the solar cells' structure only allow them to be sliced in a specific way, an optimization is performed to find the best place to slice the solar cell, forming the main wing and the flap. More details can be found in -

[Design optimization of flap configuration in samara autorotating wing with multi-functional aerodynamic structure](https://doi.org/10.1109/AIM.2019.8868777) in _IEEE International Conference on Advanced Intelligent Mechatronics 2019_.

### 4. A Flapless SAW Design

![Flapless SAW](https://www.dropbox.com/s/96inldjmmmpsrzg/Flapless%20SAW.png?raw=1)

An alternative to using a flap for glide trajectory control of SAW is explored by using a thrust unit. The thrust unit can provide a precise and directional forces, which can be used to effectively change the tip path plane of the autorotating platform. The optimum location of the thrust unit is found via the use of Genetic Algorithm, with the cost function being mainly the glide slope and stability of the platform. Simulations and experiments are performed and the results can be found here -

- [Concurrent optimization of mechanical design and control for flapless samara-inspired autorotating aerial robot](https://doi.org/10.1109/AIM43001.2020.9158860) in _IEEE International Conference on Advanced Intelligent Mechatronics 2020_.

### 5. Optimized Glide Slope and Diving Mode

![GlideSlope](https://www.dropbox.com/s/0rph0w03cdo3wlp/GlideSlope.png?raw=1)

SAW is a platform that uses a single actuator (a flap) and its only driving force is gravity. This puts SAW in the same category as other platforms relying on gravitational potential energy to make their journey, such as parafoils and gliders. Unlike the parafoils and gliders which may use two or more actuators, SAW only uses one. We attempt to achieve the maximum potential of SAW platform, striving to achieve the best glide 

![Dive](https://www.dropbox.com/s/m9ni5xbp1cunr7o/Dive.png?raw=1)



## Single Actuator Monocopter (SAM)

The idea to achieve controllable flight with a single actuator is one that is fancied by many and achieved by a few recently. SAM brings flight efficiency and dynamic stability of the craft to the table.

### 1. Efficient 5-DOF Controllable Flight with Single Actuator

![SAM](https://www.dropbox.com/s/ye4fb12epe6fn4o/ExperiSAM.png?raw=1)

### 2. Semi-rigid Foldable Wing Structure

Currently a work in progress. Details will be updated at a later stage.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA5NTgxMDk4LC00OTM3MzY0MzcsLTE1Mj
IxNjEyMjcsMTExMjU4MDU4OCwtMTM3MjE5OTg3MiwtMTIyNzY1
MzY1NSwxNzIxNDA1MjMyLDEyNTQzOTk1MDksLTEyNDIyODAwMD
csMjc5MDY3OTE5XX0=
-->