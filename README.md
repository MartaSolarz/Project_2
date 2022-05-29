# Project 2 - Ordinary Differential Equations #
A project for laboratory classes in ordinary differential equations - the phase portraits.

Task:
Consider the size of the bacterial population in a changing environment, which is described by the following equation:

$\dot{x}=\begin{cases} 2x & t\leq0\\(1−t)\cdot2x+t\cdot2x\cdot(1-\frac{x}{7}) & t \in (0,1) \\ 2x\cdot(1-\frac{x}{7}) & t\geq1\end{cases}$

where time $ t \in [−1, 2] $ is scaled in an arbitrary unit of time, while $ x (t) $ is given in millions of individuals.

The $ [- 1, 2] $ time frame is divided into 3 periods:
* $ [- 1, 0] $ - unlimited environment,
* $ (0, 1) $ - transition period,
* $ [1, 2] $ - restricted environment.

Based on the portrait / phase portraits, discuss the population dynamics throughout the time period and in each period: how the population develops depending on the initial condition, when the constraint appears, how the constraint changes.
