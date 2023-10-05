# LQR-LQG-design-process

This code demonstrates the process of designing LQR/LQG.
Users can change the state space on the code to their own state space. However, one should notes the dimension of the weight matrices Q1 and Q2

###Short introduce about LQR/LQG
#### LQR
LQR stands for Linear Quadratic Regulator, which is an optimal control strategy for linear dynamic systems. It aims to minimize a quadratic cost function defined over an infinite time horizon.

#### LQG
LQG combines the principles of LQR with optimal state estimation in the presence of noise. Specifically, it addresses situations where:

The system is controlled optimally using LQR.
The system state is not directly measurable and is estimated using a Kalman filter.

