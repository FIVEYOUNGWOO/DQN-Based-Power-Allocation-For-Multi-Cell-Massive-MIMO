## DQN-based-Power-Allocation-For-Multi-Cell-Massive-MIMO

We have implemented a DRL-based power allocation system for massive MIMO in cellular networks, utilizing Open-AI Gym and TensorFlow frameworks.

This implementation reinforcement learning algorithm is designed solely for the Deep Q Network (DQN).

(* This code offers the initial draft version of the DRL-based power allocation technique on multi-cell networks.)

## Hyperparameters
- (N) is the number of cells equal to the number of BSs
- (M) is the number of BS transmission antennas
- (K) is the number of users in a cell
- (BW) is bandwidth
- (NF) is the power of noise figure [dBm]
- (Ns) is the Number of samples as TDD interval
- (min_p) is Minimum transmission power [dBm]
- (max_p) is Maximum transmission power [dBm]
- (num_p) is the number of action space size
