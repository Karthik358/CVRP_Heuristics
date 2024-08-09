Vehicle Routing Problem aims to find an optimal schedule for a fleet of vehicles to deliver
goods to customers. In order to solve the Vehicle Routing Problem, we propose two variants
Farthest First Nearest Cluster (FFNC) and Nearest First Nearest Cluster (NFNC) alongside 
the sweep heuristic which comes under the family of cluster-first, route-second
approaches and Clarke and Wright savings heuristic. For cluster-first, route-second
algorithms the customers are divided into subsets in the first stage so that each set has the
maximum number of customers that can be served within a tour. In the following step, all
assigned clusters' optimal tours are calculated. The two proposed variants differ in the
clustering phase. For routing phase MTZ TSP formulation is used for all the three methods. We
compare the performance of the savings and sweep heuristics and two distance based
variants of sweep that are considered in this paper.

Details of data files and code files
- "cVRPsTW250_1.csv" contains dataset used in this paper.
- IE716_sweep_hue_clustering.ipynb contains python code for clustering phase for classic sweep (Anticlockwise and Clockwise directions).
- CVRPTW_rand_dist.ipynb contains python code for clustering phase for distancebased variants FFNC and NFNC.
- IE716_sweep_routing.ipynb contains python code for routing phase for all the four algorithms.
- IE716_savings.ipynp contains python code for Clarke and Write savings algorithm.
