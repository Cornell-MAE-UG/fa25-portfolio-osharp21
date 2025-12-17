---
layout: project
title: Wind Turbine Blade Design (MAE 4272)
description: Wind-tunnel-tested blade design using BEM modeling and Weibull-weighted evaluation
technologies: [MATLAB, QBlade, CAD, Wind Tunnel Testing]
image: /assets/images/blade_cad_thumbnail.png
---

For MAE 4272 (Fluids & Heat Transfer Lab), our team designed and tested small horizontal-axis wind turbine blades for a controlled wind-tunnel setup. The goal was to maximize power extraction over a realistic wind environment modeled by a Weibull wind-speed distribution (k=5, c=5), while meeting strict geometric and operational constraints including a 6-inch maximum blade span, hub compatibility, fixed-speed operation (Ω < 2000 rpm), and a nacelle-clearance axial envelope requirement.

### Design Process
We began with a baseline blade design to establish a manufacturable geometry and a consistent evaluation workflow. I built a MATLAB blade-element momentum (BEM) pipeline that ingests airfoil polars generated in the free software QBlade (across relevant Reynolds numbers) and produces predicted power curves across wind speeds. Candidate twist profiles and airfoil options were evaluated using Weibull-weighted performance, emphasizing expected power across the most probable inflow conditions rather than optimizing a single wind speed.

Operating speed was treated as a design variable within the imposed limit. Across the configurations we evaluated, predicted power increased as rotational speed approached the 2000 rpm constraint, supporting a target operating condition near 2000 rpm. The final blade retained the Blade7 chord distribution and NACA 4412 airfoil, while modifying twist to target an approximately constant 6° angle of attack along the span at the design condition.

### Testing and Results
Blades were tested in the wind tunnel using a torque brake and controlled operating conditions. Torque and rotational speed measurements were used to compute mechanical power (P = τΩ) and generate power curves for comparison against model predictions.

**Power curve comparison (model screening across twist profiles):**  
<img src="{{ '/assets/images/power_curves_twist_sweep.png' | relative_url }}" alt="Power curve comparison" style="width: 700px; max-width: 100%; height: auto;">

**Final blade CAD (geometry used for fabrication/testing):**  
<img src="{{ '/assets/images/blade_cad.png' | relative_url }}" alt="Blade CAD" style="width: 520px; max-width: 100%; height: auto;">

### My Contribution
I developed and owned the MATLAB-based BEM power-curve pipeline and the Weibull-weighted comparison method used to screen candidate designs. I ran parameter sweeps (including twist iterations and Ω sweeps), generated predicted power curves, and used the results to support selection of the final twist strategy and operating speed target.

**Wind-tunnel testing photos:**  
![Wind tunnel photo]({{ "/assets/images/blade_test_photo_1.jpg" | relative_url }})
<img src="{{ '/assets/images/blade_test_photo_1.jpg' | relative_url }}" alt="Wind tunnel photo" style="width: 520px; max-width: 100%; height: auto;">
