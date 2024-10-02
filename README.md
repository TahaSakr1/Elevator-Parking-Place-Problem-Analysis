# Elevator Parking Place Problem Analysis

## Project Overview

The **Elevator Parking Place Problem Analysis** project analyzes elevator movement data to solve the "Parking Place Problem" for elevators. The goal is to identify the most efficient parking floors for elevators during periods of inactivity. This analysis provides insights into elevator performance, movement patterns, and potential inefficiencies in parking locations.

Using Python and Plotly, the project performs various data analysis tasks on elevator journeys, including:

- Tracking movements between floors.
- Detecting periods of inactivity.
- Identifying the most frequently used parking floors when elevators are idle.
- Generating insightful visualizations such as heatmaps and bar charts.

## Visualizations

Below are the interactive visualizations generated from the elevator movement data. Click the links to explore them:

- [Elevator 1 - Cumulative Rides Parking Floor](https://tahasakr1.github.io/Elevator-Parking-Place-Problem-Analysis/elev_1_cuml_rides_parking_floor_3.html)
- [Elevator 1 - Frequency Analysis (Sankey)](https://tahasakr1.github.io/Elevator-Parking-Place-Problem-Analysis/elev_1_freq_analysis_parking_floor_3(sankey).html)
- [Elevator 2 - Cumulative Rides Parking Floor](https://tahasakr1.github.io/Elevator-Parking-Place-Problem-Analysis/elev_2_cuml_rides_parking_floor_1.html)
- [Elevator 2 - Frequency Analysis (Sankey)](https://tahasakr1.github.io/Elevator-Parking-Place-Problem-Analysis/elev_2_freq_analysis_parking_floor_1(sankey).html)
- [Combined Bar Plot of Elevator Frequencies](https://tahasakr1.github.io/Elevator-Parking-Place-Problem-Analysis/combined_bar_plot.html)

These visualizations give insights into how frequently the elevators travel between floors and where they tend to park during periods of inactivity.

## Project Structure

The project is structured as follows:

- **code/**: Contains the Python scripts used for analysis and visualization generation.
- **data/**: Contains elevator movement datasets (note: excluded from GitHub repository for privacy).
- **graphs/**: Contains the HTML files for visualizations.
- **images/**: Contains any images used in the project documentation.
- **docs/**: Contains the HTML visualizations hosted via GitHub Pages.
- **requirements.txt**: List of dependencies required to run the project.

## Running the Code Locally

To run the code locally:

1. **Install dependencies**:
   - Make sure you have Python installed.
   - Install required Python packages by running:
     ```bash
     pip install -r requirements.txt
     ```

2. **Place your data files**: 
   - Ensure that the elevator data is in the correct format and placed in the `data/` directory.

3. **Run the Jupyter Notebooks or Python Scripts**: 
   - Use the provided notebooks in the `code/` folder to replicate the analysis and generate the visualizations.

## Technologies Used

- **Python**: Data analysis and manipulation.
- **Pandas**: Handling and processing the elevator movement data.
- **Plotly**: For generating interactive visualizations such as bar plots, heatmaps, and Sankey diagrams.
- **GitHub Pages**: To host and share interactive HTML visualizations.

## Conclusion

This project provides valuable insights into elevator parking behavior and identifies areas for efficiency improvements. The visualizations are designed to help optimize the use of elevators, reduce idle time, and improve overall performance.

Feel free to explore the visualizations and code. Contributions and suggestions are always welcome!
