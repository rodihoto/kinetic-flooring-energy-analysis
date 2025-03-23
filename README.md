# Harnessing Footsteps: Analyzing Kinetic Flooring's Impact on Urban Energy

Imagine a city where every step you take helps power its infrastructure. This project analyzes the potential of kinetic flooring technology (like Pavegen) to harvest energy from pedestrian movement on high-traffic walkways such as the Brooklyn Bridge in New York City.

## Project Overview

Kinetic flooring systems generate electricity from foot traffic. This analysis estimates the energy output using real pedestrian count data and explores its potential applications in sustainable urban development (e.g., powering street lights or IoT sensors).

## Objectives

- Analyze pedestrian foot traffic data from the Brooklyn Bridge.
- Estimate daily energy generation using piezoelectric principles.
- Visualize trends and energy potential.
- Demonstrate practical applications for smart cities.

## Dataset

**Source:** NYC Open Data  
[Brooklyn Bridge Automated Pedestrian Counts](https://data.cityofnewyork.us/Transportation/Brooklyn-Bridge-Automated-Pedestrian-Counts-Demons/6fi9-q3ta)

## Methodology

1. Load and clean pedestrian count data.
2. Aggregate foot traffic by day.
3. Estimate energy generated per footstep (3 joules).
4. Convert to watt-hours (1 Wh = 3600 J).
5. Visualize energy trends and potential savings.

## Key Assumption

- **3 joules** per footstep (based on Pavegen documentation)
- **1 Wh = 3600 J**
- Energy output = `(footsteps × 3 J) / 3600`

## Project Structure


## How to Run

1. Clone the repository:

2. Install dependencies:

3. Run the Jupyter Notebook in the `/notebooks` directory to see analysis and visualizations.

## Results Preview

- Daily foot traffic trends
- Estimated daily energy production (in Wh)
- Interactive visualizations using Plotly

## Technologies Used

- Python
- Pandas
- Plotly
- Matplotlib
- Jupyter Notebooks

## References

- [Pavegen Official Website](https://www.pavegen.com/)
- [NYC Open Data](https://data.cityofnewyork.us/)
- [IEEE Smart Materials Research](https://ieeexplore.ieee.org/document/9134524)

## License

This project is licensed under the MIT License.
