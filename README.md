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

### Source Code
The code is uploaded as a Zip file 'cloudsim-3.0.3.zip'.Its based on the [cloudsim toolkit Tag 3.0.3](https://github.com/Cloudslab/cloudsim/releases/tag/cloudsim-3.0.3) from CLOUDS Labortaory in Melbourne.Few of the files are updated to implement Reinforcement Learning.

### Logs
The experimental Logs are updated in [Logs](/Logs) .
The text logs from the Lrmmt and Lr-RL experimental runs are logged and converted to csvs and saved in this folder.

### Notebooks
The [Analysis_Notebooks](/Analysis_Notebooks) has all the files used to analyze the experiments and create statistial Reports using the experimental Logs.

