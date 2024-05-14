# Generalising health events by using frequent itemset mining

This repository is the official implementation of the methods in the Master's Thesis "Generalising health events by using frequent itemset mining" by Oliver-Erik Suik.

## Overview
This notebook implements the method section described in the thesis, and it presents the analysis and results for generalizing health events in OMOP format using Frequent Itemset Mining.

## Contents
The project is organized into the following Notebooks:
- fim_impl.ipynb: Implementation of a model for creating frequent itemsets and clustering
- health_event_timelines.ipynb: Plotting initial and generalized health timelines of patients 
- test_cases.ipynb: Location of test use cases for the validation of clusters
- datasource.ipynb: Mock data in OMOP format

## Requirements
Ensure you have the following dependencies installed:
- Python
- Jupyter Notebook
- Additional Python Libraries

You can install the required Python libraries using pip:
```setup
pip install -r requirements.txt
```

## Usage
1. Navigate to the repository directory:
```usage
cd fim-health-data
```
2. Start the Jupyter Notebook server:
```usage
jupyter notebook
```
3. Open the datasource file in the Jupyter Notebook interface, run the cells to seed mock data. 
4. Open the fim_impl file in the Jupyter Notebook interface, set the values for the parameters and run each cell sequentially to execute the analysis.

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback regarding this research, feel free to contact:
- Oliver-Erik Suik
- GitHub: OliverSuik

