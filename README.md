# Entity Resolution Project

This repository contains the work from a project focused on entity resolution using various algorithms. The objective was to explore, implement, and compare different techniques for matching and linking records across datasets.

## Project Overview

Entity resolution is the process of identifying and merging duplicate records that refer to the same entity across different data sources. This project implements several algorithms and compares their effectiveness.

### Key Components

- **Explorations**: Jupyter notebooks that explore and implement different entity resolution algorithms.
  - Algorithms explored include TF-IDF Vectorizer, Difflib, FuzzyWuzzy, Jellyfish, and RecordLinkage.
  - Each notebook details the methodology and results for the specific algorithm.

- **Results**: CSV files that contain the results of applying the different algorithms to the datasets.
  - These results demonstrate the accuracy and performance of each technique.

- **Source Code**: Python scripts that implement the core entity resolution algorithms.
  - Modular and reusable code for each algorithm, designed for easy integration into other projects.

- **Presentations**: Summaries and visualizations of the project’s findings, useful for understanding the overall approach and results.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages listed in `Requirements.txt`

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/shijianfei1413/entity-resolution.git
   cd entity-resolution
2. Install the required packages:
   ```sh
   pip install -r Requirements.txt
3. Explore the notebooks or run the Python scripts:
- Jupyter notebooks are in the Explorations folder.
- Python scripts are in the src folder.

### Usage

- Run Notebooks: Open any notebook in the Explorations folder to see the implementation and results of the algorithms.
- Analyze Results: CSV files in the Results folder provide detailed outputs for different techniques, allowing for comparison and analysis.

### Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or create pull requests.

### License

This project is licensed under the MIT License. See the LICENSE file for details.
