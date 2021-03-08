# Engineering Computations Module 3

_Engineering Computations_ is a collection of stackable learning modules, flexible for adoption in different situations.
It aims to develop computational skills for students in engineering, but it can also be used by students in other science majors.
The course uses the Python programming language and the Jupyter open-source tools for interactive computing.

After the two foundation course modules, equipping you with the coding patterns for numerical computing, this module is our launching pad to investigate _the dynamics of change and motion_ using computational thinking.

## Module 3: Tour the dynamics of change and motion

_Tackling the dynamics of change with computational thinking._

**Pre-requisite: learning module [*EngComp 1](https://github.com/engineersCode/EngComp1_offtheground) of our collection.**

> Get an interactive session in [MyBinder.org](https://mybinder.org/) with these course materials by clicking on the button below.
> Select the folder `notebooks_en` to access the five lessons of this course as fully executable Jupyter notebooks.
>
> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/engineersCode/EngComp3_tourdynamics/master)

* **Join the [open online course](http://go.gwu.edu/engcomp3)** on our _Open edX_ platform
* **Get a PDF version to print**: _Engineering Computations Module 3: Fly at change in systems._ figshare.
 https://doi.org/10.6084/m9.figshare.5673526
 
### [Lesson 1](http://go.gwu.edu/engcomp3lesson1): Catch things in motion

Working with images and videos in Python using `imageio`. Interactive Matplotlib figures in the notebook, and capturing mouse clicks on images for digitizing an object's position. Computing velocity and acceleration from position captures: a falling ball, and projectile motion. Computing numerical derivatives using differences. Free-fall acceleration from real data.

### [Lesson 2](http://go.gwu.edu/engcomp3lesson2): Step to the future

Computing velocity and position from accelerometer data: a roller-coaster ride. Using the `subplot()` function go draw more than one plot in the same figure. **Euler's method** for initial-value problems, and Taylor expansion showing first-order accuracy. The second-order differential model for an object in free fall written as two first-order differential equations, leading to a vector form. General design of a code to solve ordinary differential equations (ODEs). Application to free fall of a tennis ball and comparison with experimental data. Improved model accounting for air resistance.

### [Lesson 3](http://go.gwu.edu/engcomp3lesson3): Get with the oscillations

Differential model of a spring-mass system without friction: state vector and system in vector form. Amplitude growth with Euler's method on oscillatory systems, and the fix: Euler-Cromer method (semi-implicit Euler).
Numerically observed order of accuracy using a convergence plot: numerical error with different time increments, ∆t.
Modified Euler's method, and observed order of accuracy.

### [Lesson 4](http://go.gwu.edu/engcomp3lesson4): Bird's-eye view of mechanical vibrations

General spring-mass systems with damping and a driving force, revealing a variety of behaviors. Presents a powerful new method to study dynamical systems based on visualizing direction fields and trajectories in the phase plane.

## Copyright and License

(c) 2017 Lorena A. Barba, Natalia C. Clementi. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE). We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
