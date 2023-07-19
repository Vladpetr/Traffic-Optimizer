# Traffic-Optimizer
Compares different strategies to optimize traffic flow in a particular section of London.

## Project Overview
Traffic engineering plays a critical role in urban design, ensuring the smooth and safe flow of traffic in cities. This project aims to optimize traffic flow in a particular section of our city by exploring and comparing different strategies. The goal is to address London's needs by proposing efficient traffic management solutions through modeling and simulation.

## Data
I selected a section of our city with multiple intersecting streets. By using tools like Google Maps, I obtained a bird's eye view of the chosen area, noting the street names and allowed directions of travel. Additionally, I conducted on-site data collection to measure traffic density in each street. I counted the total number of cars passing in each direction during a predetermined time period and computed the average. I also observed the behavior of traffic lights at intersections to understand the previous strategies implemented by traffic engineers.

## Model and Simulation
The following tasks were completed:
* [x] Adopted a grid-based simulation approach, making necessary assumptions such as considering curved streets as straight in the model.
* [x] Utilized acceleration and deceleration models on straight roads.
* [x] Designed rules for car turns at intersections and traffic light behavior.
* [x] Adjusted model parameters to match the real-world data, ensuring a reasonably realistic simulation outcome.
* [x] Interpreted the empirical results obtained from our simulations.
* [x] Visualized and described the empirical results while considering the impact of random variations inherent in Monte Carlo simulations.
* [x] Compared the empirical results with theoretical estimates and discussed any disparities.
