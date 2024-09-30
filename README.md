# Harry-Kane---Penalty-Data-collection-and-Analysis

# Harry Kane Penalty Project

## Overview

This project aims to analyze and predict the outcomes of Harry Kane's penalty kicks. By leveraging historical data and machine learning techniques, we explore various factors influencing penalty directions and generate synthetic data representing all possible scenarios for Kane's future penalties.

## Data Collection

Data for this project has been meticulously collected, encompassing various aspects of Harry Kane's penalty-taking behavior. The dataset includes:

- **Penalty Outcomes:** Results of each penalty taken (goal, miss)
- **Penalty Locations:** The location of the penalty kick (left, center, right)
- **Game Context:** Situational data such as match pressure, scoreline, and time
- **Psychological Factors:** Information on player decision-making and external pressures during penalties

The data is stored in the `data` folder and consists of:

- Raw data file containing the collected penalty information
- A DataCard that provides detailed descriptions and insights about the dataset

## Synthetic Data Generation

To simulate various penalty scenarios and predict outcomes, a Jupyter Notebook (`PredictKanePenalty.ipynb`) is included. This notebook contains the code to generate synthetic data based on the patterns observed in the collected dataset. It allows us to explore hypothetical situations and evaluate how different variables impact penalty outcomes.

## Model Loading

The project includes pre-trained models located in the `model` folder:

- **KNN Model (n=7):** A K-Nearest Neighbors model that has been optimized for predicting penalty outcomes with `n=7` neighbors. Better genralized to the trained dataset.
- **KNN Model (n=8):** An additional K-Nearest Neighbors model with `n=8` neighbors for comparative analysis. The model with the highest accuracy.

## Getting Started

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open the Jupyter Notebook and execute the cells to generate synthetic data, load the models and predict outcomes.

## Conclusion

This project serves as a comprehensive analysis of Harry Kane's penalty kicks, offering insights into the factors that influence outcomes. The generated synthetic data will facilitate further research and modeling efforts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
