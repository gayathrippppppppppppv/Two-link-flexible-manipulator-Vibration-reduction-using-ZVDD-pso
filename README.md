# Two-link-flexible-manipulator-Vibration-reduction-using-ZVDD-pso

## Problem Statement 
A two-link flexible manipulator carrying a payload exhibits vibrations (caused by Rapid joint motion , Structural flexibility , during trajectory tracking)and due to Payload influence

## Objective

To model a two-link flexible manipulator using the Assumed Mode Method (AMM)

To study the effect of payload on vibration characteristics

To reduce vibration using:
- ZVDD input shaping
- PSO-optimized PD controller

To develop a real-time simulation and Image animations
To implement and validate the controller on hardware using Arduino and sensors

## Methodology
Define physical parameters of the flexible manipulator

Model link deformation using Assumed Mode Method

Generate desired trajectory (circular + linear path)

Apply inverse kinematics to obtain joint trajectories

Design ZVDD input shaper based on system natural frequency

Use PSO to optimize PD controller gains

Simulate system in MATLAB

Implement control algorithm on hardware prototype

Validate vibration reduction experimentally

## Code 
[Flexible_2Link_FEM_PSO_FINAL.pdf](https://github.com/user-attachments/files/30020964/Flexible_2Link_FEM_PSO_FINAL.pdf)

## Output 

<img width="494" height="298" alt="fig7_pso_convergence" src="https://github.com/user-attachments/assets/de0602ea-21ed-44b4-824d-afb23fe0c2d5" />
<img width="494" height="298" alt="fig6_zvdd_effect" src="https://github.com/user-attachments/assets/05632b5b-c064-4ac3-a102-4352515e1961" />
<img width="494" height="299" alt="fig5_torque" src="https://github.com/user-attachments/assets/706a7f75-ae4e-4eb4-8cec-a02af099d65c" />
<img width="494" height="298" alt="fig4_velocity" src="https://github.com/user-attachments/assets/b98d4dc6-4ac1-4f31-9a43-4c6540a83a69" />
<img width="494" height="298" alt="fig3_joint_tracking" src="https://github.com/user-attachments/assets/bf4d3239-66a6-4f2c-88f7-0f510694888f" />
<img width="494" height="299" alt="fig2_trajectory" src="https://github.com/user-attachments/assets/55e7537a-9513-41dc-b101-92aec271d01e" />
<img width="494" height="299" alt="fig1_vibration_response" src="https://github.com/user-attachments/assets/ca4f584f-68ec-4dc8-839e-5dd050d76f71" />




