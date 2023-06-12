# Numerical Integration with Python

This repository contains a Python script that can compute numerical approximations of definite integrals using various methods such as left endpoint, right endpoint, midpoint, trapezium, and Simpson's method. 

## Description

The function `num_int()` is capable of computing an approximation of the definite integral of a function on a given interval using a specified numerical integration method.

The function accepts a Riemann integrable function `f`, an interval `[a, b]`, a number of evenly-spaced intervals `n` to split `[a, b]`, a sequence representing the partition of the domain `part`, and a numerical integration `method` to be applied using `part`.

