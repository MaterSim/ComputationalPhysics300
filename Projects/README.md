Here is the list of projects.

## Project 1, Animation of Wave propagation
[Lec04](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_04_Python_intro_IV.ipynb)
Write an python code to provide an interactive interface to simulate the propogation of waves due to the dropped pebbles in a pool. This interface should allow the user to do the following
- `drop pebble` button to set up the position of the first pebble
- `start` buttion to initiate the animation of the wave propogation
- `drop pebble` button to pause the animation and set up the position of the second pebble
- `continue` button to continue to model the wave proprogations due to two pebbles
- `terminate` button to terminate this simulation

One can refer to the [bokeh](https://bokeh.pydata.org/en/latest/docs/gallery.html) and [K3D](https://github.com/K3D-tools/K3D-jupyter) for the hints to realize these functions.
![video](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/videos/wave_propogation.gif)

## Project 2, Mandelbrot set
[Lec04](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_04_Python_intro_IV.ipynb)
Write a code to show the dynamical behavior of each point in the entire complex plane and introduce the property of [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set) and [Julia set](https://en.wikipedia.org/wiki/Julia_set).

![plot](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/img/mandelbrot_set.png)

## Project 3, Gaussian Quardrature 
[Lec05](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_05_integral.ipynb)
Write a wiki page to introduce Gaussian Quardrature from the fundamental of mathematics, and give some applications.

## Project 4, Numerical derivatives 
[Lec06](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_06_derivative.ipynb)
Write a wiki page to introduce different approaches to compute the derivative and describe their applications to some specific problems.
- Finite difference
- Complex step
- Cauchy integral formula
One can find the references from the [wikipedia page](https://en.wikipedia.org/wiki/Numerical_differentiation)

## Project 4, B-spline Interpolation
[Lec07](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_07_interpolation.ipynb)
Write a wiki page to introduce B-spline Interpolation method and show its application.

## Project 5, Generalized Linear regression
[Lec08](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_08_fitting.ipynb)
Write a wiki page to derive the math for linear regression and generalize it to polynomial regression. Choose a dataset to test the performance of regressions with order 1, 2, 3.

## Project 6, Simulation of Powder X-ray diffraction
[Lec08](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_08_fitting.ipynb)
Write a wiki page to explain how to compute the X-ray diffraction and write a code to compute the powder XRD pattern for FCC, BCC, HCP crystals.

## Project 7, Random numbers generation
[Lec13](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_13_random_number1.ipynb)
Introduce the modern approach to generate the random numbers on computer.

## Project 8, Local optimization
[Lec15](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_15_optimization1.ipynb)
Introduce the ideas of at Least two optimization methods from the following
- Gradient Descent
- Conjugate Gradient
- BFGS
- Quasi Newton
- L-BFGS

Write the numpy code to solve the minima for the [Rosenbrock function](https://en.wikipedia.org/wiki/Rosenbrock_function), and compare the results with scipy.minimize library. 

## Project 9, Global optimization on LJ clusters
[Lec19](https://github.com/sabaronett/2017-cmp/blob/master/Lec_19_global_optimization_III.ipynb)
Introduce the basin hopping algorithm and apply the code to do the following
- choose three numbers between 10 - 30
- find the parameters which could lead to the global minimum.
- plot the energy evolution as a function of steps
- Speed up the code based on vectorization, numba, explicit gradient functions

## Project 10, Machine Learning
[Lec24](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/Lec_24_ML4.ipynb)
Write a code based on numpy to solve either the classification or regression problem from the open ML datasets.
- classification
- regression

By choosing one of the following methods:
- Artificial Neural Networks
- Random Forest
- Support Vector Machine
- Gaussian Process

Compare the results with sklearn.


![plot](https://github.com/qzhu2017/ComputationalPhysics300/blob/master/img/nn.gif)

