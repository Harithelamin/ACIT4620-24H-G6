## Required Libraries

To run this project, you will need to install the following Python libraries:

- `pandas` - For data manipulation and analysis.
- `numpy` - For numerical computing.
- `matplotlib` - For plotting and visualizing data.
- `scikit-fuzzy` - For fuzzy logic operations and control systems.
- `seaborn` - For statistical data visualization used with `matplotlib`.
- `scikit-learn` - For machine learning tasks, such as metrics, and evaluation.
- `pickle` - For storing and opening dataset
- `nbimporter` - For importing Jupyter Notebooks as Python modules.

### Installation
You can install the required libraries using `pip`. Here is a sample installation command:

```bash
pip install pandas numpy matplotlib scikit-fuzzy seaborn scikit-learn nbimporter
```

# Data set can be found at: 
https://www.kaggle.com/datasets/arbaaztamboli/loan-approval-dataset


## How to Run the Code

### `dataset_manager.ipynb`

The `dataset_manager.ipynb` file is responsible for importing the datasets, filtering the data, and checking for missing values. It then stores the cleaned data as a pickle file called `filtered_df.pkl`.

This file does not need to be run for the code to function correctly. However, if any adjustments to the dataset are required, it should be done within this file. 
To run the file, run all cells from top to bottom, or use the notebook function **Run All**.

### `fuzzification.ipynb`

The `fuzzification.ipynb` file handles everything in correlation to the fuzzy system fuzzyfication, membership functions, and rules. 

This file does not need to be run for the code to function either, as it the functions defined in this file is imported to main.
To run the file, run all cells from top to bottom, or use the notebook function **Run All**.

### `main.ipynb`

The `main.ipynb` file, is where everything is put together. This file does some basic data exploration and visualize them as well as showing the membership functions and results from the fuzzification system. 
To run the file, run all cells from top to bottom, or use the notebook function **Run All**.
