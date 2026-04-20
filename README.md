# Ideal Function Mapping

## Overview
This project analyzes structured datasets by loading training, ideal, and test data into a SQLite database, identifying the best-fitting ideal functions, and mapping test data to those functions based on deviation thresholds.

## Project Goal
The goal of this project is to match training functions with the most suitable ideal functions using the least squares method, then assign test data points to the best available ideal function.

## Methods Used
- Data loading and extraction from CSV files
- SQLite database setup with SQLAlchemy
- Least squares error comparison
- Test-data mapping with deviation thresholds
- Interactive visualization with Bokeh

## Tools & Libraries
- Python
- Pandas
- NumPy
- SQLAlchemy
- SQLite
- Bokeh
- Jupyter Notebook

## Dataset
The project uses three structured datasets:
- `train.csv`
- `ideal.csv`
- `test.csv`

## Repository Structure
- `ideal_function_mapping.ipynb` — main notebook with data loading, matching, mapping, and visualization

## Main Steps
1. Extract and inspect the dataset files
2. Load CSV files into a SQLite database
3. Identify best-fitting ideal functions for each training function
4. Map test data to ideal functions using deviation thresholds
5. Visualize training data, ideal functions, and mapped points

## Highlights
- Combined Python data analysis with SQL-based data storage
- Applied least squares logic to identify best-fit functions
- Structured the workflow from raw files to final mapped outputs
- Added interactive visualization with Bokeh

## Notes
This project was completed as part of academic coursework and is presented here as a portfolio project demonstrating Python, SQL, structured data processing, and analytical problem-solving.
