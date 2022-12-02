### An Optimal Multi-UAV Deployment Model for UAV-assisted Smart Farming

#### Index Terms: *Optimal UAVs, Interference Management*

##### Assumptions

* K-means is used for specified K (i.e. UAVs) based on the location of nodes.
* More UAVs: signal collision, high cost. Fewer UAVs: more path loss, less coverage
* The nodes are performing Random Waypoint Model.

##### Basic Idea:

![]([images/An Optimal Multi-UAV Deployment Model.png](https://github.com/Liam-Tian/ML-in-Livestocks-Management-using-UAV-Paper-Review-/blob/main/images/An%20Optimal%20Multi-UAV%20Deployment%20Model.png))

To narrow the range of the UAV numbers, the author defines multiple criteria in terms of interference level and path loss. Specifically, they use SINR, bandwidth and service delay to indicate the interference level, and path loss to indicate the data transferring quality or coverage. The paper does not give a clear threshold of each criteria. But the algorithm suggests that starting from 1 UAV, will choose the minimum number of UAVs which meets the criteria.

