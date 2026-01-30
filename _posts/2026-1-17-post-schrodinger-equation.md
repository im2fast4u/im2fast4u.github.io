---
title: "The Schrodinger Equation"
date: 2026-1-17
---

The Schrodinger equation is another great discovery that explains how a particle state changes over time. It was formulated in the 1920s by Erwin Schrodinger.

## Partial Derivatives
Since Schrodinger's equation, and many other equations in quantum physics include **partial derivatives**, I shall explain it here. Derivatives simply tell you the rate of change of something, or how things change over time. However, partial derivatives only differenciate the terms with the variable it's respected to. The other variables act as constants.

Let's take the partial derivative of $4x^3 + 3xy^2 - 4y$ with respect to $x$. The first term has $x$, so we differenciate it and get $12x^2$. We differenciate the second term, but remember $y^2$ acts as a constant, so we get $3y^2$. The last term is a constant and the derivative of a constant alone in 0. Therefore, our answer is $12x^2 + 3y^2$. If we differentiate with respect to $y$, we get $6xy - 4$.

## Time-Dependent
The time-dependent Schrodinger equation, or the most common one is for describing the rate of change of the state of a particle. The wave function $\psi$ represents the state of particle. The partial derivative (represented with backward 6s) acts on the wave function. It's with respect to time, so it finds how the state $\psi$ changes over time. The equation is usually written as:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $i\hbar \frac{\partial }{\partial t}\Psi (\mathbf{r},t)=\hat{H}\Psi (\mathbf{r},t)\$

where $i$ is the imaginary unit, $\hbar$ is the reduced planck's constant, and $\hat{H}$ is the hamiltonian operator (the total energy: potential + kinetic).

## Time-Independent

## Conclusion

[Need a refresh on complex numbers? Click here.](https://www.premmehta.com/post-complex-numbers/)
