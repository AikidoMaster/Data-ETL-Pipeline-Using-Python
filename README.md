
# Data ETL Pipeline with Python

This repository demonstrates how to develop a Data ETL (Extract, Transform, Load) pipeline using Python. The pipeline extracts data from the Fashion-MNIST dataset, transforms it, and loads it into an SQLite database.

## Overview

The ETL process consists of:
1. **Extracting**: Loading the Fashion-MNIST dataset using Keras.
2. **Transforming**: Normalizing pixel values and reshaping the data.
3. **Loading**: Storing the transformed data into an SQLite database.

## Files

- `etl_pipeline.ipynb`: Jupyter Notebook demonstrating the ETL pipeline process.
- `fashion_mnist.db`: SQLite database file containing the transformed data.

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```

2. **Install required libraries**:
   ```bash
   pip install tensorflow numpy sqlite3 pandas
   ```

3. **Run the notebook**:
   Open `etl_pipeline.ipynb` in Jupyter Notebook or JupyterLab and execute the cells to see the ETL process in action.

## Usage

1. Load the Fashion-MNIST dataset.
2. Normalize and reshape the data.
3. Create an SQLite database and store the data.
4. Retrieve and display the data from the database.



```

