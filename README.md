# Pendulum on Cart Control System - README

## Overview
This project involves the control of a pendulum on a cart system, commonly known as an inverted pendulum. The primary objective is to stabilize the pendulum in an upright position while keeping the cart stationary. This is achieved through a control algorithm designed to manage the system's dynamics effectively.

<img src="https://github.com/user-attachments/assets/2517fab5-492e-4808-8a83-f9937c2469fb">

---

## System Description
The system consists of:
1. **Pendulum**: A rod pivoted on a cart, which can swing freely.
2. **Cart**: Moves along a horizontal track, controlled to stabilize the pendulum.
3. **Control Algorithm**: Designed to ensure the pendulum remains upright and the cart stays stationary.

---

## Key Features
- **Stabilization**: The control algorithm ensures the pendulum remains in the upright position.
- **Stationary Cart**: The cart is controlled to remain stationary, minimizing movement.
- **Simulation**: The system is simulated to test and validate the control strategy.

---

## Files and Instructions
1. **Model Files**:
   - `PenOnCart.slx`: Simulink model of the pendulum on cart system.
   - `inverted_pendulum_on_a_cert_TASK_1.m`: MATLAB script for task-specific configurations.

2. **Running the Simulation**:
   - Open the Simulink model (`PenOnCart.slx`).
   - Run the `inverted_pendulum_on_a_cert_TASK_1.m` script to load parameters.
   - Simulate the model and observe the stabilization of the pendulum and cart.

3. **Control Algorithm**:
   - The control algorithm is implemented within the Simulink model.
   - Adjust parameters as necessary to optimize performance.
     

---

## Dependencies
- MATLAB R2019b or later.
- Simulink.

---

## Notes
- Ensure the solver settings are configured appropriately for accurate simulation results.
- The model assumes ideal conditions; adjust parameters if real-world conditions differ.

---

## License
This project is open-source and available under the MIT License. Feel free to modify and distribute it as needed.

---

For questions or feedback, please contact the project maintainer.
