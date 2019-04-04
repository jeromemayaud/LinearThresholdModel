# LinearThresholdModel
Measuring the performance of the Linear Threshold Model to predict information diffusion through a social network

To run the model, the final cell executes a series of simulations, for which performance metrics are calculated.

Descriptions of files user has to provide: 

- 'fname' is a list of the node IDs of all members in your social network
- 'pl_fname' is a list of the node IDs of the Peer Leaders in your network
- 'convert_fname' is a list of the node IDs of the members who were observed to be converted
- 'nc_fname' is a list of the node IDs of the members who were NOT observed to be converted
- 'all_nodes_fname' is a complete list of all named and unnamed node IDs in the network

Parameters that must be changed in the model:
- 'time_limit' is the time limit after which the simulation ends (usually set at 100)
- 'number' is thr number of times each simulation is iterated (usually set at 100)
- 'number_of_simulations' is the number of separate simulations you want to average over (usually set at 10)
