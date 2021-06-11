# VehicleRoutingProblem

Solution Background & Problem Statement:

As many companies focus on their core business, warehousing and transport activities are many times outsourced to third-party logistics providers. Road transport is still the most used mode of transport for distribution of goods. Logistics providers want to use their fleet of vehicles in the most efficient way, so route optimisation comes into the picture. In the operations research literature, the Vehicle Routing Problem (VRP) is one of the most studied problems because of both its practical relevance and its computational complexity. The issue concerns the distribution of goods between hubs and customers along a set of routes for a fleet of vehicles where an objective function is optimized. The objective function could me minimizing total routing cost,  minimizing total distance travelled, etc, while taking into real life constraints like maximising capacity utilization of all the fleet, meeting customer demand, ensuring timely delivery, etc. Solving a basic vehicle routing problem involves two elements: the assignment of all customers to a trip and the sequence in which each customer or location is visited.  
Real-life cases face uncertainties in load of orders, in travel time and in availability of the vehicles. The route planner may be confronted with data disturbances in the routine activities. An optimal solution produced by using deterministic input variables may be infeasible or not good enough in case a situation has changed.

Thus, we would like to focus on a variant of the Vehicle Routing Problem – i.e. Clustered Vehicle Routing Problem, where customers are divided into clusters based on geo location. While doing so, the solution may determine vehicles to consecutively visit all customers belonging to the same cluster. This approach may work very well for clusters where the load of delivering orders is high, however, fewer orders scattered across multiple clusters may not able to meet the constraint of ensuring the fleet capacity if optimally utilized. For solving this problem, there is a need to: 
1.	Automatically create clusters based on load (no. of orders to be picked up / delivered) in a given hub where route planning is being done
2.	Sort all orders based on the clusters being defined
3.	Create trips with definitive routes for the vehicles and assign all orders to these trips

Expectations: 
1. Select the most suited solution(s) for route planning & clustering from GitHub for the above stated problem
2. Build a solution for automating generation of clusters based on load (no. of orders to be picked up / delivered)
3. Run a simulation for 5000 orders to be delivered to different locations in a single day in a particular geographical territory with multiple clusters using a fixed number of vehicles. By minimizing the total distance travelled by all vehicles & ensuring maximum capacity of each of the vehicles assigned to trips is utilized. 
4. Assume 100 vehicles available for the route planning at the hub
5. Output of the simulation – 
- Each of the 5000 order must be assigned to a trip (which is assigned to a single Vehicle)
- Each trip must have routes & sequencing of orders defined to minimize the amount of distance travelled. 
6. The project must be accompanied with a summary document of the open source projects used and what changes were implemented or what modules were built to arrive at the simulation results

