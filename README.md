# Numerical-Analysis-Tennis-Simulation
This project, completed as part of the Numerical Methods course (SF1514) at KTH, analyzes the trajectory of a tennis serve considering air resistance and gravity.

Technical Features:

1. ODE Simulation: Solved system of differential equations for ball motion using both manual implementations (Runge-Kutta) and built-in solvers (ode45).

2. Root-finding: Implemented the Secant Method and used fzero to calculate the optimal launch angle for a 1-meter net clearance.

3. Interpolation: Used Cubic Splines to accurately determine height at specific x-coordinates (the net and baseline).

4. Sensitivity Analysis: Conducted error estimation (störningsräkning) to validate the precision of the numerical results.
