# Python-Decal-FA25-RLC-Circuits
Python DeCal Fall 2025 Final Project: Modeling Inductance in an RLC Circuit
# Project Description
The following project utilizes oscilloscope data measuring the transient response of an inductor in an underdampened and overdampened system. It contains dampened sinusoidal and simple exponential functions to generate models for both systems respectively, and fits the models to their respective systems using SciPy's optimization functions. 
# Required Packages and Installations

Numpy (numerical expressions contained in functions and for all other general numerical analyses)

Matplotlib (plotting model results) 

Scipy (optimizations of functions to data) 
# Running The Code

Import measured/experimental data into python file of your choice and plot as needed

Import exp_decay and/or exp_decay_1 functions for overdamped RLC circuit system data

OR 

Import voltage_equation for underdamped RLC circuit system data

Fit voltage/equation/exp_decay to your data using scipy.optimize.curve_fit

Interpolate the model as needed using scipy.interpolate.interp1d and/or animate your graph using FuncAnimation and PillowWriter from matplotlib.animation