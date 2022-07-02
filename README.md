# Project 2 - Ordinary Differential Equations #
### *A project for laboratory classes in ordinary differential equations - the phase portraits.* ###

### Task description ###

Consider the size of the bacterial population in a changing environment, which is described by the following equation:

1. $\dot{x}= 2x$ for $\space t\leq0$ 
2. $\dot{x}= (1−t)\cdot2x+t\cdot2x\cdot(1-\frac{x}{7})$ for $\space t \in (0,1)$ 
3. $\dot{x}= 2x\cdot(1-\frac{x}{7})$ for $\space t\geq1$ 

where time $t \in [−1, 2]$ is scaled in an arbitrary unit of time, while $x(t)$ is given in millions of individuals.

The $[- 1, 2]$ time frame is divided into 3 periods:
* $[- 1, 0]$ - unlimited environment,
* $(0, 1)$ - transition period,
* $[1, 2]$ - restricted environment.

Based on the portrait / phase portraits, discuss the population dynamics throughout the time period and in each period: how the population develops depending on the initial condition, when the constraint appears, how the constraint changes.

### Python modules used ###

* matplotlib.pyplot
* numpy
* sympy

*Author: Marta Solarz*
