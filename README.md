# Mobian Park-and-Ride System Expansion

## Introduction
Mobian aims to solve the last mile problem for commuters with its unique Park & Ride (P&B) system. This project focuses on identifying optimal locations for potential hubs in Amsterdam to maximize user demand coverage. Mobian's initiative to expand Amsterdam's park-and-ride system is underpinned by our data-driven optimization model. Our analysis proposes seven new hubs to cater to 9,587 riders, emphasizing the importance of hubs like Mobihub Sloterdijk, Louwesweg, Parking90, and Parking55. Notably, our research indicates that adding more than 10 hubs does not significantly enhance demand coverage.

## Methodology
Our model aims to maximize hub demand within set limits. We utilized Pyomo to identify hubs that maximize covered demand. Data collection included junctions, hubs, and Points of Interest (POIs) locations, demand, travel distances and times. Constraints included travel time limits and maintaining existing hubs. The model set two binary variables, x and y, indicating if a hub meets the restriction (1) or not (0).

## Findings and Recommendations
Our model recommends opening 7 new hubs to effectively cover the demand of 9,587 commuters. We observed diminishing returns in demand coverage with more than 10 hubs, suggesting a maximum of 10 hubs for optimal demand coverage. Priority should be given to hubs Mobihub Sloterdijk, Louwesweg, Parking90, and Parking55. Qpark Oostpoort and Parking134 are also important but less critical.

## Advantages and Limitations
- **Advantages**: The model can be extended to other cities, supporting data-driven decision-making.
- **Limitations**: Fixed model parameters require periodic adjustment. Current limitations include not accounting for fluctuating commuter demand, public transportation flows, and operational costs.

### Future Considerations
- Prioritize operational costs in future model optimizations.
- Adapt model parameters to accommodate fluctuating demands and diverse transportation flows.

## References
- Mobian, Park & Ride System, 2017.
- Pyomo Optimization Modeling: [Pyomo Documentation](https://www.pyomo.org/)
