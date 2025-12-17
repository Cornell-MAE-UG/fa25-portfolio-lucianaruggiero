---
layout: project
title: Blade Design
description: esign, analysis, manufacturing, and wind tunnel testing of a 6-inch wind turbine blade optimized for power output at low Reynolds numbers. 
technologies: [SolidWorks, MATLAB, ANSYS, Wind Tunnel Testing, Machining]
image: /assets/images/blade.jpg
---


### Project Overview

For this project, our team was tasked with designing a wind turbine blade that maximized mechanical power output in the Big Blue wind tunnel while remaining structurally safe and manufacturable. The blade needed to operate within strict geometric constraints, including a maximum radius of 6 inches and clearance requirements relative to the nacelle. Our design targeted an operating speed of 500 RPM at a representative wind speed derived from a Weibull distribution, balancing aerodynamic performance with practical testing limitations.

<img
  src="{{ '/assets/images/blade-cad.jpg' | relative_url }}"
  alt="Blade CAD model"
  class="project-image"
/>


### Design Process

We selected the NACA 4418 airfoil due to its favorable lift-to-drag characteristics at low Reynolds numbers and its suitability for manufacturing. Using MATLAB, we developed a blade design that incorporated nonlinear taper and spanwise twist to maintain an effective angle of attack along the blade. The resulting geometry was translated into CAD through iterative profile placement and lofting. We then evaluated aerodynamic loading and pressure distribution using ANSYS, confirming smooth pressure contours and stresses well below the resin’s flexural strength, indicating a large structural safety margin.

<img
  src="{{ '/assets/images/power-curve.jpg' | relative_url }}"
  alt="Blade CAD model"
  class="project-image"
/>


### Testing Summary

The fabricated blade was tested in the Big Blue wind tunnel using a magnetic particle brake to apply controlled loading. We collected RPM, torque, voltage, current, and wind speed data across multiple operating points to generate power curves at several wind speeds. Although vibration limited our ability to reach peak RPM safely, the measured power curves showed the expected nonlinear increase in power with rotational speed and followed consistent trends across tests. The experimental results aligned well with our simulation predictions and provided insight into how pitch and twist affected the operating point.

<img
  src="{{ '/assets/images/ansys.jpg' | relative_url }}"
  alt="Blade CAD model"
  class="project-image"
/>


### My Contribution

I led the ANSYS simulations used to evaluate aerodynamic pressure distribution and structural safety, ensuring the blade could withstand expected operating loads. I also assisted with power curve analysis and interpretation of experimental results, helping connect simulation predictions with observed performance during wind tunnel testing.

