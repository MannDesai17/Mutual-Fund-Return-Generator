# Mutual-Fund-Return-Generator
README

This repository contains code for analyzing mutual fund data. The analysis is done using Python and PySpark.

## Getting Started

### Prerequisites

- Python 3.x
- PySpark
- pandas

### Installing

To install PySpark and pandas, run the following commands:

```
!pip install -q pyspark
!apt-get install -y openjdk-11-jdk-headless -qq > /dev/null
```

```
!pip install pandas
```

## Running the Code

The main code file is `final_mf_ai.ipynb`. This file contains the code for analyzing mutual fund data. To run this file, open it in Jupyter Notebook or Google Colab and execute the cells.

The code does the following:
- Loads mutual fund data from a CSV file.
- Filters the data for a specific date or fund.
- Calculates the returns for a specific fund for the past 1 month, 3 months, 6 months, 1 year, and 3 years.

## Built With

- Python
- PySpark
- pandas

## Author

- [Mann Desai](https://github.com/MannDesai17)
