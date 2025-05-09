# Quantum Experiment Data Analysis

This repository contains a Jupyter notebook for exploring and cleaning a mock dataset of gedanken quantum computing experiments. The focus is on preparing the data for downstream analysis by addressing missing values, visualizing distributions, and handling outliers.

## Contents

- `quantum_eda.ipynb`: The main notebook containing data analysis.
- `quantum_data.csv`: Mock dataset of quantum experiment.
- `data_set_maker.ipynb`: Notebook containing code for creating the mock data.
- `README.md`: Project overview and usage instructions.

## Dataset Description

The `quantum_data.csv` file includes various parameters recorded from quantum computing experiments, such as (these are really placeholders for all practical purpose, do not bother with the meanings per se):

- `experiment_id`: Identifier for the experiment
- `qubit_count`: Number of qubits used
- `fidelity`: Gate fidelity metric
- `coherence_time_us`: Coherence time in microseconds
- `gate_error_rate`: Error rate of quantum gates
- `temperature_k`: Temperature in Kelvin
- `measurement_method`: Categorical description of the measurement approach

## Goals of the Analysis

1. Inspect the data and understand its structure.
2. Identify and deal with missing values (imputation).
3. Visualize distributions and detect outliers.
4. Handle the outliers (IQR method).
5. Generate aggregated summary statistics for each experiment.
6. Create a few visualizations exploring the various relationships between the parameters/variables.

## Dependencies

- pandas
- numpy
- seaborn
- matplotlib

