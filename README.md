# Titanic Data Analysis and Visualization Project

A comprehensive Jupyter notebook-based data analysis and visualization project exploring the Titanic dataset using Python data science libraries.

## Overview

This project performs in-depth exploratory data analysis (EDA) and visualization on the Titanic dataset. It includes data loading, cleaning, missing value analysis, and various statistical and visual explorations to understand patterns and relationships in the data.

## Dataset

The project uses the classic Titanic dataset with two CSV files:
- **train.csv**: Training dataset with survival outcomes
- **test.csv**: Test dataset for predictions

Located in the `Data/` directory.

## Project Structure

```
Titanic_Visualization_Project/
├── titanic_analysis.ipynb          # Main Jupyter notebook with all analysis
├── Data/
│   ├── train.csv                   # Training dataset
│   └── test.csv                    # Test dataset
├── virtual_enviroment/             # Python virtual environment
└── README.md                        # This file
```

## Requirements

The project uses a Python virtual environment with the following key libraries:

- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - 2D plotting and visualization
- **seaborn** - Statistical data visualization
- **jupyter** - Interactive notebook environment

## Installation & Setup

### 1. Create/Activate Virtual Environment

If you haven't already set up the virtual environment:

```bash
python -m venv virtual_enviroment
```

Activate the virtual environment:

**Windows (PowerShell):**
```bash
.\virtual_enviroment\Scripts\Activate.ps1
```

**Windows (Command Prompt):**
```bash
.\virtual_enviroment\Scripts\activate.bat
```

**Mac/Linux:**
```bash
source virtual_enviroment/bin/activate
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter notebook
```

## Usage

### Running the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open `titanic_analysis.ipynb` in your browser.

Alternatively, you can use Jupyter Lab:

```bash
jupyter lab
```

## Notebook Contents

The analysis notebook includes the following sections:

1. **Library Imports** - Loads all required data science libraries
2. **Version Check** - Displays library versions
3. **Data Loading** - Imports and displays training and test datasets
4. **Basic Information** - Dataset shape, columns, and data types
5. **Missing Values Analysis** - Identifies and quantifies missing data
6. **Missing Values Visualization** - Heatmaps and bar charts showing data gaps
7. **Statistical Analysis** - Summary statistics and distributions
8. **Survival Analysis** - Examination of survival rates across different features
9. **Passenger Demographics** - Analysis of age, gender, class distributions
10. **Correlations & Relationships** - Statistical relationships between variables
11. **Advanced Visualizations** - Multiple visualization types for deeper insights

## Key Analysis Areas

- **Data Quality**: Missing value patterns and data completeness
- **Passenger Demographics**: Age, gender, class analysis
- **Survival Patterns**: Factors influencing survival outcomes
- **Correlations**: Relationships between different variables
- **Visualizations**: Histograms, heatmaps, scatter plots, and more

## Technologies Used

- **Python 3.x** - Programming language
- **Jupyter Notebook** - Interactive computing environment
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib** - Plotting library
- **Seaborn** - Statistical visualization

## Notes

- The notebook includes informative print statements for tracking data loading and processing steps
- Warnings are filtered to maintain clean output
- All visualizations are embedded directly in the notebook

## Author

Created for data analysis and visualization practice.

## License

This project uses the publicly available Titanic dataset.

---

For questions or improvements, feel free to modify and expand this project!
