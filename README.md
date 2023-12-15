# Solving CFD Problems with Python and Various Numerical Methods
 <p align="center">
    <a href="https://img.shields.io/badge/Status-Work%20In%20Progress-red">
      <img src="https://img.shields.io/badge/Status-incomplete-red"/>
    </a>
    <a href="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
      <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white"/>
    </a>
    <a href="https://img.shields.io/badge/License-MIT-orange">
      <img alt="License" src="https://img.shields.io/badge/License-MIT-orange" />
    </a>
    <a href="https://img.shields.io/badge/Grade-A%2B-yellowgreen">
      <img alt="Grade" src="https://img.shields.io/badge/Grade-A%2B-yellowgreen" />
    </a>
<br />
# Overview
This project aims to solve Computational Fluid Dynamics (CFD) problems related to the heat equation, wave equation, and heat transfer using Python. Various numerical methods, including Finite Volume Method, Runge-Kutta 4 (RK4), Finite Difference Method, and Finite Element Method, have been implemented for accurate and efficient simulations.

# Implemented Methods
## Heat Equation
The heat equation describes the distribution of heat over time within a given region. I utilized the Finite Difference Method to discretize the partial differential equation and simulate the evolution of temperature. The RK4 method was employed for time integration, providing a stable and accurate solution.

$$
\frac{\partial C}{\partial t} = D \frac{\partial^2 C}{\partial x^2}
$$

$$
\frac{\partial C}{\partial x} = 0
$$


$$
\rho \frac{dv}{dt} - \mu \left(\frac{d^2 v}{dr^2} + \frac{1}{r}\frac{dv}{dr}\right) = -\nabla p
$$


$$
\rho C_p \frac{\partial T}{\partial t} + \rho C_p \bar{v} \cdot \nabla T + \nabla \cdot \left(-k \nabla T\right) = Q
$$
1. Numerical Method: Finite Difference Method
2. Time Integration: Runge-Kutta 4 (RK4)
# Wave Equation
The wave equation models the propagation of waves through a medium. Using the Finite Difference Method for spatial discretization and RK4 for time integration, I simulated the behavior of waves, showcasing the importance of accurate numerical methods in capturing wave dynamics.
1. Numerical Method: Finite Difference Method
2. Time Integration: Runge-Kutta 4 (RK4)
#Heat Transfer
Heat transfer is a critical aspect of many engineering applications. Implementing the Finite Volume Method allowed me to simulate heat transfer scenarios efficiently. This method discretizes the domain into control volumes, providing a robust approach for solving complex heat transfer problems.
1. Numerical Method: Finite Volume Method
# Finite Element Method
1. Numerical Method: Finite Element Method

##Contributions
Contributions are welcome! Feel free to submit issues or pull requests.

##License
This project is licensed under the MIT License.
