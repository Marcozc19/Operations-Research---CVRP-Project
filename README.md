# Operations-Research---CVRP-Project
## Overview
This Repo contains the content of my undergraduate dissertation, "Visual Attractiveness Optimization in CVRP(Constraint Vehicle Routing Problem)". Visual Attractiveness is a subjective optimzation objective that attempts to incorporate innovative human logic in to the NP-hard routing problems. The final disseration was written in Chinese which is also uploaded to this Repo. The dissertation contains multiple sections including a literature review, theoretical exporation, mathematical modeling, and implmentation through case study.
## Code Structure
There are multiple code files in this repo, each of their functionalities are as followed:
### Initial Solution
1. Initial Solution.py: Implements a traditional C-W algorithm for initial CVRP solution.
2. Random_Initial_Solution.py: C-W algorithm with random distribution for initial CVRP solution.
3. NewInitialSolution.py: Initial solution that takes visual attractiveness into consideration.
### Vistual Attractieness Optimization
1. CompactnessOptimizerNew.py: Route compactness optimizer.
2. Ruin_and_Restructure.py: Route overlap optimizer.
3. GLSAVA.py: Guided local search algorithm with visual attractiveness optimization for overall routes.
4. InterRouteOptimizer.py: Single route optimization using simulated annealing algorithm.
### Traditional Optimization
1. GLS.py: Guided local search for benchmark CVRP solution.
### Others
1. Information.py: Key route indicator calculator.
2. MapDisplay.py: Route visualization using folium.
3. RearrangeExcel: Excel helper for generating new test cases.
