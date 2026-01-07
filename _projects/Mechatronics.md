---
layout: project
title: Mechatronics Robot 
technologies: [Arduino, C++, CAD, Rapid Prototyping, Sensors, Embedded Systems]
image: /assets/images/robot.jpg
---


## Autonomous Robot Design
#### Overview

This project was completed as part of MAE 3780 (Mechatronics) and involved the design, construction, and programming of an autonomous robot capable of navigating a structured environment and collecting objects. The system required close integration between mechanical design, electrical systems, and embedded software control. The final robot demonstrated reliable performance under time constraints and repeated physical interactions, highlighting robust system-level design.

<hr>


#### Mechanical Design

The robot chassis was designed to support a multi-level architecture that separated power, control, and sensing components to improve reliability, accessibility, and troubleshooting. Structural decisions prioritized mechanical stability while remaining within strict size constraints.

An aluminum bumper and side panel system guided objects into the robot while protecting the drivetrain from collisions. The geometry balanced durability, weight, and functional volume, allowing the robot to interact repeatedly with its environment without mechanical failure.

<img
  src="{{ '/assets/images/robcad.jpg' | relative_url }}"
  alt="Blade CAD model"
  class="project-image"
  style="display:block; float:none; clear:both; margin: 24px 0 32px 0; max-width: 600px;"
/>


<hr>

#### Electrical System & Integration

The electrical system was organized to maintain clean wiring, stable power delivery, and easy access to components during debugging and iteration. Multiple power sources were used to isolate high-current motor loads from sensitive control electronics, reducing noise and preventing brownout conditions.

Layered component placement and disciplined wire routing minimized failure risk and enabled rapid identification of loose connections or faults during testing.

<img
  src="{{ '/assets/images/arduino.jpg' 
  | relative_url }}"
  alt="Blade CAD model"
  class="project-image"
  style="display:block; float:none; clear:both; margin: 24px 0 32px 0; max-width: 600px;"
/>


<hr>

#### Control Logic & Software

The robot’s control logic was implemented using Arduino-based embedded programming. Software coordinated motor actuation, sensor input, and timed motion sequences to execute a repeatable navigation strategy.

Interrupt-based sensing was used to detect field boundaries, and the codebase was structured around modular motion and behavior functions. This approach improved readability, debugging efficiency, and overall control reliability during iterative testing.

<img
  src="{{ '/assets/images/systemflow.jpg' 
  | relative_url }}"
  alt="Blade CAD model"
  class="project-image"
 style="display:block; float:none; clear:both; margin: 24px 0 32px 0; max-width: 600px;"
/>


<hr>

#### Outcome

The final robot demonstrated integrated mechanical, electrical, and software subsystems operating as a cohesive platform. The project earned a final score of 100 and strengthened practical skills in system-level design, rapid iteration, and translating theoretical concepts into a functional electromechanical system.