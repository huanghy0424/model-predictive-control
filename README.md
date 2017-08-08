# Model-Predictive-Control
To control a robot to move along a straight line (in 2D) by modeling it as a unicycle (thereby deriving a set of discrete-time dynamic equations), and optimizing the cost function over tracking accuracy and control effort with and without a feedback control.

Written as part of an assignment for ROB310 - Introduction to Robotics at the University of Toronto.

# Equations

The robot (or car) is modelled as a unicycle with sampled inputs `vk` and `wk` at time step `k` which represents predefined forward velocity and turn rate, respectively. 


