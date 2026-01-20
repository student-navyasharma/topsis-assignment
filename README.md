# TOPSIS Decision Support System – Assignment Project

## Overview

This assignment implements the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method using Python.

The project consists of:

- A command-line TOPSIS program  
- A Python package published on PyPI  
- A web service using Flask  
- A Google Colab notebook for analysis and visualization  

The objective is to rank multiple alternatives based on multiple criteria using a scientific and automated decision-making approach.

---

## What is TOPSIS?

TOPSIS is a Multi-Criteria Decision Making (MCDM) technique used to identify the best alternative from a set of options.

The best alternative is the one that:

- Is **closest to the ideal solution**
- And **farthest from the worst solution**

It is widely used in finance, engineering, management, and data science for ranking problems.

---

## Steps of the TOPSIS Algorithm (Brief)

1. Read the input dataset  
2. Normalize the decision matrix  
3. Apply weights to each criterion  
4. Determine ideal best and ideal worst values  
5. Calculate distance from ideal best and worst  
6. Compute TOPSIS score  
7. Rank alternatives based on score  

Formula used:
Topsis Score = S− / (S+ + S−)

Where:  
S+ = distance from ideal best  
S− = distance from ideal worst  

---

## Implementation in this Assignment

### 1. Command Line Program

A Python script that performs TOPSIS using command line arguments.

Example:

```bash
python topsis.py data.csv 1,1,1,1,1 +,+,-,+,+ output.csv

2. Python Package (PyPI)

The program is packaged and published on PyPI for easy installation and usage.

Package name:

Topsis-Navya-102303313


Installation:

pip install Topsis-Navya-102303313


Usage:

topsis data.csv 1,1,1,1,1 +,+,-,+,+ output.csv


3. Web Service

A web application developed using Flask that allows users to:

Upload a dataset

Enter weights and impacts

Provide email address

Receive the TOPSIS result CSV via email

This makes the system accessible without using the command line.


4. Google Colab Notebook

A Jupyter notebook created using Google Colab that:

Implements the same TOPSIS logic

Displays result tables

Generates ranking graphs

Exports result CSV

This notebook is used for analysis, visualization, and academic documentation.


Conclusion

This project provides a complete decision support system using TOPSIS with:

Automation via CLI

Distribution via PyPI

Web-based access

Visual analysis using Colab

It demonstrates both theoretical understanding and practical implementation of multi-criteria decision making.


Author

Navya Sharma
Roll Number: 102303313
