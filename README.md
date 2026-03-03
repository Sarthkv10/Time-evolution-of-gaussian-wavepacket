# Time-evolution-of-gaussian-wavepacket

Aim

To numerically solve the Time-Dependent Schrödinger Equation (TDSE) and simulate the time evolution of a Gaussian wave packet confined inside an infinite potential well, using the Crank–Nicolson implicit scheme.

Physical Model

The Schrödinger equation is given by $i \hbar \frac{\partial \psi}{\partial t}=-\frac{\hbar^2}{2m} \frac{\partial^2 \psi}{\partial x^2}+ V(x)\psi$​

We consider a 1D infinite potential well defined as:

$$V(x) =\begin{cases}0, & 0 < x < L \\\infinity, & \text{otherwise}\end{cases}$$

Then we define initial wave function as -

$$\psi(x,0) = A \exp\left(\frac{(x - x_0)^2}{4\sigma_0^2}+ i k_0 x\right)$$

Where:

- $A$ is the normalization constant  
- $x_0$ is the initial center of the wave packet  
- $\sigma_0$ is the initial width  
- $k_0$ is the initial wave number  
