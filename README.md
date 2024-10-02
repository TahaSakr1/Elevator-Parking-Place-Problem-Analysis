# Elevator Parking Place Problem Analysis

## Description
This project focuses on analyzing elevator movement data to solve the **"Parking Place Problem"** for elevators. The goal is to understand the patterns in elevator usage, identify frequently used parking floors, and analyze inefficiencies during idle times. Using **Python** and **Plotly**, the project performs data analysis on elevator movements between floors, detecting periods of inactivity, and providing visual insights into the most frequent parking floors.

### Key Features:
- **Inactivity Detection**: Identifies periods when the elevator is idle and determines the most used parking floors.
- **Visualizations**: Generates various visual insights, including heatmaps and bar charts, to display elevator movement patterns and parking behavior.
- **Data Filtering**: Filters out invalid or irrelevant elevator movement data for cleaner and more efficient analysis.

## Project Structure
Elevator-Parking-Place-Problem-Analysis/
│
├── code/
│   ├── Elevator Parking Analysis.ipynb    # Jupyter notebook containing the analysis code
│   └── (other Python scripts if any)
│
├── data/                                  # Folder for datasets (not uploaded to GitHub)
│   └── (your datasets will be stored here)
│
├── graphs/                                # Generated visualizations
│   ├── combined_bar_plot.html             # Bar plot comparing elevator parking patterns
│   ├── elev_1_cuml_rides_parking_floor.html   # Parking patterns for Elevator 1
│   ├── elev_2_cuml_rides_parking_floor.html   # Parking patterns for Elevator 2
│   └── (other HTML graphs)
│
├── images/                                # Related images
│   └── (images showcasing the analysis results or documentation)
│
├── .gitignore                             # Ignores sensitive files (e.g., datasets)
├── README.md                              # This README file
└── requirements.txt                       # List of required Python packages

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Elevator-Parking-Place-Problem-Analysis.git
   cd Elevator-Parking-Place-Problem-Analysis
