# Masters Thesis
### Energy Aware VM Selection Policies for Data Centres.

This Thesis  aims
to evaluate an approach to reduce data centre energy consumption
using reinforcement learning algorithms to optimize the virtual machine (VM) selection process.VM selection is the process of selecting an VM from a overloaded host and moving it to another host.An optimized selection of VMs can lead to a few overloaded hosts and this leads to a reduction in energy usage. 

Two reinforcement learning algorithms, Q-learning and SARSA 
were implemented in the [cloudsim toolkit](https://github.com/Cloudslab/cloudsim). Subsequent experiments employed two distinct policies—epsilon greedy and SoftMax—to determine the most effective hyperparameters, specifically the learning rate (alpha) and the discount factor (gamma).
The proposed algorithm results
in a energy saving of 18% compared to the Lr-Mmt approach. The
results of this thesis conclude that the RL algorithm can intelligently
optimize the VM selection process and thereby reducing the energy
consumption in the data center.

Language:Java

RL Algorithms: Q learning and SARSA
