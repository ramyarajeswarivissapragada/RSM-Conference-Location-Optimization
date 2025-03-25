# RSM Conference Location Optimization Project

## Overview
This project aims to optimize the selection of a conference location for RSM US LLP's post-pandemic professional gathering, focusing on balancing cost efficiency and logistical feasibility.

## Project Objectives
- Select an optimal conference location among multiple options
- Minimize overall costs, including:
  - Travel expenses
  - Accommodation costs
  - Lost client billable hours
- Determine the optimal number of rooms to book

## Data Sources
The project utilized four key datasets:
1. Employees Table (3,579 employees)
2. Office Locations Table (75 unique locations)
3. Flights Table (768,000+ flight records)
4. Conference Locations Table (28 conference centers)

## Methodology
### Data Preprocessing
- Standardized city names
- Removed duplicate entries
- Harmonized time zones
- Filtered data to relevant employees and flights
- Calculated travel and opportunity costs

### Optimization Approach
- Developed a cost matrix for employee travel
- Implemented a Facility Location Problem using Constrained Optimization
- Considered multiple constraints and objectives

## Key Findings
### Optimal Conference Location
**Atlanta (Americas Mart)** was selected as the optimal location, offering:
- Lowest total cost
- Minimal lost billable hours
- Most efficient travel arrangements

### Room Booking Strategy
- Optimal number of rooms: 1,709
- Accounts for potential attendance variations (85-100% attendance)

## Limitations and Future Scope
- Current model assumes cheapest available flights
- Does not account for:
  - Personal travel preferences
  - Return flight costs
  - Shared accommodation options

## Recommendations for Future Analysis
- Incorporate round-trip flight costs
- Consider personal travel preferences
- Explore shared accommodation possibilities

## Project Team
- Harish Bhupalam
- Ramya Rajeswari Vissapragada
- Sumi Batas
- Surya Madhuri Susarla

## Technical Details
- Optimization Method: Constrained Optimization
- Programming Language: Python
- Visualization Tool: Tableau
