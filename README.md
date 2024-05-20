# Network Visualization of Core Topics and Lectures

## Overview
This repository contains Python scripts and data used to create network visualizations of lectures related to the core topic of Hydro Power. The visualizations help map out how different lectures and core topics are interconnected, providing insights into the academic structure of a Geography Master's program.

## Contents
- **data**: Contains CSV files with data on lectures and core topics.
  - `Core_Topics_and_Lectures.csv`
  - `Core_Topics_and_Lectures_weighted.csv`
- **src**: Contains Python scripts for generating network visualizations.
  - `1_static_code_final.py`: Script for a simple static network.
  - `2_static_code_final_ects_weighted.py`: Script for a static network with ECTS weighting.
  - `3_static_ects_and_connection_weighted_final.py`: Script for a static network with ECTS and connection weighting.
  - `4_interactive_plot_final.py`: Script for an interactive network visualization.
- **images**: Contains output images and the interactive HTML file.
  - `static_plot_simple_final.png`
  - `static_plot_weighted_final.png`
  - `static_ects_and_connection_weighted_final.png`
  - `interactive_plot_final.html`
- **docs**: Contains the project report.
  - `Thomi_Network_Science_Assignment.docx`

## Getting Started

### Prerequisites
- Python 3.x
- Required Python libraries:
  - pandas
  - networkx
  - matplotlib
  - adjustText
  - pyvis

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/network-visualization.git
