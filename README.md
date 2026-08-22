# Runge-Kutta-Nyström Methods for Second-Order ODEs with Periodic Solutions

> **Master's Thesis** | AGH University of Krakow, Faculty of Applied Mathematics (2026)  
> **Author:** Wioletta Małgorzata Sudoł  
> **Advisor:** dr Michał Braś

## Abstract & Keywords

This master's thesis is devoted to the study, construction, and implementation of Runge-Kutta-Nyström methods whose coefficients depend on both the step size and the natural frequency of the system. Since standard schemes with constant coefficients are often insufficiently accurate for oscillatory problems, their construction is based on trigonometric polynomials, which ensures precise integration of periodic systems.

The first chapter presents the necessary theoretical concepts and classical numerical methods. The second chapter is devoted to the formal formulation of the class of frequency-dependent methods, the derivation of conditions for their coefficients, and the analytical construction of a two-stage trigonometric method. The third chapter presents the results of numerical experiments conducted on several test problems, including a harmonic oscillator with external forcing and the Kepler problem. All numerical simulations were performed using Python code. The source code is included in a file attached to this thesis.

**Keywords**: Second-order ordinary differential equations, Trigonometric polynomials, Runge-Kutta-Nyström methods, Trigonometric order, Harmonic oscillator

## Repository Structure

* Complete Python implementation - `Wioletta_Sudoł_Symulacje_Numeryczne.ipynb`
* Full Master's Thesis PDF - `Wioletta_Sudoł_Praca_Magisterska.pdf`
