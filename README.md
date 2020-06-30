# Infinite Linear Car Parking Problem with PPOagent

Niu, M.Y., Boixo, S., Smelyanskiy, V.N. et al. **Universal quantum control through deep reinforcement learning**. npj Quantum Inf 5, 33 (2019).
https://doi.org/10.1038/s41534-019-0141-3

In this paper, they use the trust region policy optimization method(Schulman, 2015), a kind of policy gradient algorithm with specific constraint called Kullback-Leibler divergence, to create a deep neural network control framework to simultaneously optimize the speed and fidelity of quantum computation against both leakage and stochastic control errors.

Inspired by steering qubits around the Bloch sphere, I would like to design a simple classical control problem before I really get hands dirty on the quantum control problem. My classical control problem is trivial. There is a car sitting on the infinite straight line, and the RL agent needs to control the pedal to speed up or slow down, steering the car to park right at the terminal point.
