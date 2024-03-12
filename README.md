# NextBillion.ai Route Optimization API vs Google Cloud Fleet Routing

The benchmarking exercise between Nextbillion.ai’s Route Optimisation Flexible API and Google Cloud Fleet Routing was carried out on the 2nd of February 2024.

Data sets and APIs used in the benchmarking exercise are available in the repo. 

## Problem Statement

The Route Optimisation APIs are tested for mock jobs and vehicles data generated for the city of Los Angeles.

It is considered that `x` number of vehicles with a max capacity of `y` no of packages needs to deliver the packages to the customer’s location across the cities.

`x` & `y` - The numbers vary wrt the scenario tested.


### Scenario 1: 57 Jobs 14 Vehicles  
This scenario considers 14 vehicles as input for fulfilling 57 jobs. A maximum capacity of 10 nos of packages per vehicle is used and the total no of packages for shipment is 619.

| **Outputs** | **Google CFR** | **NextBillion** |
| --- | --- | --- |
| Vehicles Utilized | 14  | 10  |
| Unassigned Jobs | Nil | Nil |
| Distance Traveled (in meters) | 252,654 | 125,484 |
| Duration (in hours) | 13  | 6   |



### Scenario 2: 150 Jobs 100 Vehicles  
This scenario considers 100 vehicles as input for fulfilling 150 jobs. A maximum capacity of nos of packages per vehicle is used and the total no of packages for shipment is 428.

| **Outputs** | **Google CFR** | **NextBillion** |
| --- | --- | --- |
| Vehicle's Utilised | 77  | 77  |
| Unassigned Jobs | 47  | 47  |
| Distance Travelled (in meters) | 7786455 | 7185241 |
| Duration (in hours) | 106 | 98  |



### Scenario 3: 200 Jobs 100 Vehicles 
This scenario considers 100 vehicles as input for fulfilling 200 jobs. A maximum capacity of 10 nos of packages per vehicle is used and the total no of packages for shipment is 619.

| **Outputs** | **Google CFR** | **NextBillion** |
| --- | --- | --- |
| Vehicle's Utilised | 63  | 63  |
| Unassigned Jobs | Nil | Nil |
| Distance Travelled (in meters) | 9,415,064 | 6,567,350 |
| Duration (in hours) | 142 | 91  |



Read more about it - [NextBillion.ai Route Optimization API vs Google Cloud Fleet Routing Blog](https://nextbillion.ai/blog/nextbillionai-route-optimization-outperforms-market-leader) 
