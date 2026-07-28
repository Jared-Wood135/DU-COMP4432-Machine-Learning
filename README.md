# DU-COMP4432

This repository are the assignments completed from University of Denver's Machine Learning course COMP4432 conducted in the Summer 2026 Quarter instructed by Dr. Lucas Sawle.

This repository **WILL NOT** house direct class resources, textbooks, and lectures, but rather, my completed assignments primarily for potential employers to see what topics/materials that I am familiar with from the class.





## Table of Contents

- [Acknowledgements](#acknowledgements)
- [Environment Setup](#environment-setup)
- [COMP4432 Overview](#comp4432-overview)
- [Known Issues](#known-issues)





## Acknowledgements

[Back to Table of Contents](#table-of-contents)

- **INSTRUCTOR:** Dr. Lucas Sawle
    - **INSTITUTION:** University of Denver 2026





## Environment Setup

[Back to Table of Contents](#table-of-contents)

Python version in both environments: `VERSION HERE`

You have two options for setting up your Python environment:

### Option 1: Conda (Recommended)

**Conda** is an open-source environment and package manager that makes it easy to manage Python versions and dependencies. If you do not already use an environment manager, you may want to familiarize yourself with one since it helps avoid conflicts and makes reproducibility easier.  I use Conda and I think it's the easiest (Though I haven't used other packages)

**Steps:**
1. Install [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
2. Clone this repository (Or just download ```environment.yml```).
3. Create the environment using the provided `environment.yml`:
	```bash
	conda env create -f environment.yml
	conda activate DU_COMP4432
	```

### Option 2: pip (Use with Caution)

You can also use `pip` with the `environment.txt` file. Using pip does not manage Python versions, so you must ensure your Python version matches the requirements.

**Steps:**
1. Ensure you are using a compatible Python version (see above).
2. Clone this repository (Or just download environment.txt).
3. Install dependencies:
	```bash
	pip install -r environment.txt
    ```





## COMP4432 Overview

[Back to Table of Contents](#table-of-contents)

- Assignment 1
	- Exploratory Data Analysis
		- Seaborn `diamonds` dataset
	- Data Preparation
	- Model Development
		- LinearRegression
	- Documentation

- Assignment 2
	- Data Preparation
		- Seaborn `diamonds` dataset
	- Model Development and Selection
		- LinearRegression
		- Lasso
		- Ridge
		- DecisionTreeRegressor
	- Hyperparameter Tuning
	- Documentation

- Assignment 3
	- Exploratory Data Analysis
		- Seaborn `titanic` dataset
	- Data Preparation
	- Model Development, Tuning, and Selection
		- SupportVectorClassifier
		- LogisticRegression
		- DecisionTreeClassifier
	- Documentation

- Assignment 4
	- Exploratory Data Analysis
		- [CS4432.csv](#https://raw.githubusercontent.com/arjayit/cs4432_data/master/bike_share_hour.csv)
	- Data Preparation
	- Model Development, Tuning, and Selection
		- LinearRegression
		- Lasso
		- DecisionTreeRegressor
		- RandomForestRegressor
	- Documentation

- Assignment 5
	- TBD





## Known Issues

[Back to Table of Contents](#table-of-contents)

- `environment.yml` and `requirements.txt` is not established yet
