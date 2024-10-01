# Aircraft Wing Airflow Simulation

## Project Overview
This project simulates the airflow around an aircraft wing using Computational Fluid Dynamics (CFD) to analyze the effect of varying the angle of attack on lift and drag forces. The goal was to optimize the aerodynamic performance of the wing at different angles to improve flight efficiency.

## Objective
- To study the effect of the angle of attack on the aerodynamic performance of an aircraft wing.
- To understand how changes in the angle impact lift and drag forces through CFD simulations.

## Process
1. **Model Creation:**
   - NACA 22112 airfoil was modeled in SolidWorks.
   - The wing was scaled to a 500 mm span, and an angle of attack variable was added for parametric analysis.

2. **Simulation Setup:**
   - Simulations were performed at angles from 0° to 20° in 2° increments using SolidWorks Flow Simulation.

3. **Analysis:**
   - Pressure distribution, lift, and drag forces were recorded.
   - A parametric study helped identify optimal aerodynamic performance.

## Results
- **Lift** increases with the angle of attack up to 14°, after which flow separation causes lift to drop.
- **Drag** continuously increases with higher angles, reducing efficiency.
- The optimal angle for lift-to-drag ratio was found to be around 10°.

## Screenshots
### Pressure Distribution at 10° Angle of Attack
![Pressure Distribution](./images/pressure_distribution_10deg.png)

### Lift vs. Angle of Attack Plot
![Lift Plot](./images/lift_plot.png)


# Artificial Heart Chamber Blood Flow Simulation

## Project Overview
This project simulates the blood flow through an artificial heart chamber using CFD. The objective was to study how different inlet velocities impact the maximum outlet velocity and blood flow distribution on the outlet wall.

## Objective
- To study the effect of varying inlet blood velocity on the maximum outlet velocity in an artificial heart chamber.
- To understand how inlet velocity affects the flow distribution at the chamber outlet.

## Process
1. **Model Creation:**
   - A simplified heart chamber model was created in SolidWorks.
   
2. **Simulation Setup:**
   - Simulated blood flow in SolidWorks Flow Simulation, with inlet velocities from 0.2 m/s to 2.0 m/s.

3. **Analysis:**
   - Examined velocity distribution and pressure profiles across different inlet speeds.

## Results
- The maximum outlet velocity increased with higher inlet speeds.
- The elastic surface decreased stress and deformation compared to the rigid surface.

## Screenshots
### Flow Trajectories in Heart Chamber
![Flow Trajectories](./images/flow_trajectories.png)


# Bracket Topology Optimization

## Project Overview
This project focuses on optimizing the topology of a bracket to reduce its mass by 60%, while maintaining structural integrity. The goal was to achieve the best stiffness-to-weight ratio using topology optimization techniques.

## Objective
- To reduce the bracket's mass by 60% through topology optimization while ensuring structural integrity.

## Process
1. **Baseline Model Creation:**
   - A 20 mm thick bracket model was created from Aluminum 2014 in SolidWorks.

2. **Static Analysis:**
   - Stress analysis was performed using a 9 mm mesh to evaluate stress points and load distribution.
   
3. **Topology Optimization:**
   - The model was optimized for weight reduction while maintaining structural stiffness.

## Results
- **Initial mass:** 3324.81 grams
- **Optimized mass:** 1651.26 grams
- Stress levels increased slightly but were acceptable for the weight reduction goal.

## Screenshots
### Baseline and Optimized Model Comparison
![Bracket Models](./images/bracket_comparison.png)


# Aircraft Seat Frame Design using Topology Optimization

## Project Overview
The aim of this project was to design an aircraft seat frame that complies with EASA CS-25.561 standards, ensuring structural integrity and reducing the weight by 80%. This is critical for improving fuel efficiency and overall aircraft performance.

## Objective
- Design an aircraft seat frame using topology optimization to reduce mass by 80% while maintaining safety and strength standards.

## Process
1. **Initial Model:**
   - Created a seat frame model in SolidWorks using Aluminum 2014-T4.

2. **Static Analysis:**
   - Stress analysis was performed with loads applied downward and forward as per aviation standards.
   
3. **Topology Optimization:**
   - Optimized the frame for weight reduction, leading to an 80% reduction in mass.
   
4. **Second Optimization:**
   - Further analysis preserved critical areas while maintaining stiffness under different load cases.

## Results
- **Initial mass:** 7256.14 grams
- **Optimized mass:** 1930.99 grams
- Weight reduced by 80%, while slightly increasing stress levels within acceptable limits.

## Screenshots
### Initial and Optimized Seat Frame
![Seat Frame Models](./images/seat_frame_comparison.png)


# Drop Test Simulations for Rigid and Elastic Objects

## Project Overview
This project involves simulating drop tests for a sphere and a cube on both rigid and elastic surfaces. The aim was to analyze stress and deformation during impact to understand how surface properties and impact angles affect damage.

## Objective
- Simulate drop tests for a sphere and cube to study stress and deformation upon impact with rigid and elastic surfaces.

## Process
1. **Sphere Test:**
   - A 50 mm radius alloy steel sphere was dropped from 1000 mm onto both rigid and elastic surfaces.
   
2. **Cube Test:**
   - A cube frame (100 mm sides) made of Aluminum 2014-T4 was dropped at 90°, 45°, and 30° angles onto both rigid and elastic surfaces.

3. **Analysis:**
   - Stress and deformation were analyzed to determine the most damaging conditions.

## Results
- **Sphere Test:** Elastic surfaces significantly reduced stress and deformation compared to rigid surfaces.
- **Cube Test:** A 30° angle on the rigid surface produced the highest stress and deformation, posing the greatest risk of damage.

## Screenshots
### Sphere and Cube Drop Test Results
![Drop Test Results](./images/drop_test_results.png)
