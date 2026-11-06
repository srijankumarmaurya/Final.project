# World Happiness Analysis (Jupyter Notebook)

A step-by-step data analysis project on the World Happiness dataset, built with Python, Pandas, Matplotlib and Seaborn in a Jupyter Notebook.

---

## Project Description

This project analyzes the World Happiness dataset using a Jupyter Notebook. The dataset ranks 158 countries by their happiness score and includes the factors that contribute to that score, such as economic output, social support and life expectancy.

The notebook is divided into six cells, one for each step of the analysis:

1. Loading the dataset
2. Exploring the dataset
3. Cleaning the dataset
4. Analyzing the happiest and least happy countries
5. Finding correlations between happiness score and other factors
6. Visualizing the results with charts

Every step runs by simply executing the cells in order. No user input is needed, so the whole analysis can be repeated with one click.

### About the Dataset

The dataset is stored in `happiness.csv` and has 158 rows (one per country) and 10 columns.

| Column | Description |
| --- | --- |
| Country | Name of the country |
| Region | Region of the world the country belongs to |
| Happiness Rank | Rank of the country based on its happiness score |
| Happiness Score | Overall happiness score of the country |
| Standard Error | Standard error of the happiness score |
| Economy (GDP per Capita) | Contribution of GDP per capita to the score |
| Family | Contribution of social support to the score |
| Health (Life Expectancy) | Contribution of life expectancy to the score |
| Freedom | Contribution of freedom to make life choices |
| Trust (Government Corruption) | Contribution of trust in government |

---

## Features

| Cell | Feature | Description |
| --- | --- | --- |
| 1 | Load the dataset | Imports the libraries and reads the CSV file into a DataFrame |
| 2 | Explore the dataset | Shows the first rows, number of rows and columns, data types, summary statistics and missing values |
| 3 | Clean the dataset | Handles missing values by dropping rows or filling with mean, median or mode, and removes duplicate rows |
| 4 | Analyze the dataset | Finds the happiest and least happy countries, and the countries with the highest and lowest GDP per capita, social support and life expectancy |
| 5 | Correlation analysis | Calculates the correlation of happiness score with GDP per capita, social support and life expectancy |
| 6 | Visualize the dataset | Creates bar charts, scatter plots and a correlation heatmap |

### Details of Each Cell

**Cell 1 – Load the dataset**

- Imports Pandas, Matplotlib and Seaborn.
- Reads the CSV file from the path stored in `file_path`.
- Removes extra spaces from the column names.
- Prints a success message, or the error if the file cannot be read.

**Cell 2 – Explore the dataset**

- Displays the first 5 rows of the data.
- Prints the number of rows and columns.
- Lists every column with its data type.
- Shows summary statistics such as count, mean, minimum and maximum.
- Shows the number of missing values in each column.

**Cell 3 – Clean the dataset**

- Shows the missing values in each column.
- Compares four ways of handling them: drop rows, fill with mean, fill with median and fill with mode.
- Removes duplicate rows and reports how many were removed.
- Applies the final cleaning: numeric columns are filled with the mean and text columns with the mode.

**Cell 4 – Analyze the dataset**

- Lists the top 5 happiest and top 5 least happy countries.
- Shows the 5 highest and 5 lowest countries for GDP per capita.
- Shows the 5 highest and 5 lowest countries for social support.
- Shows the 5 highest and 5 lowest countries for life expectancy.

**Cell 5 – Correlation analysis**

- Prints the correlation between happiness score and GDP per capita.
- Prints the correlation between happiness score and social support.
- Prints the correlation between happiness score and life expectancy.

**Cell 6 – Visualize the dataset**

- Bar chart of the 10 happiest countries.
- Bar chart of the 10 least happy countries.
- Scatter plots of happiness score against GDP per capita, social support and life expectancy.
- Heatmap showing the correlation between all numeric variables.

---

## Technologies Used

| Technology | Purpose |
| --- | --- |
| **Git** | Version control for tracking changes in the project |
| **GitHub** | Hosting the project repository |
| **VS Code** | Code editor used to write and run the notebook |
| **Python** | Programming language used for the whole project |
| **Jupyter Notebook** | Running the code cell by cell and showing the output below each cell |
| **Pandas** | Data loading, cleaning and analysis |
| **Matplotlib** | Plotting scatter plots and charts |
| **Seaborn** | Bar charts and the correlation heatmap |

---

## Concepts Used

| Concept | Description | Where it is used |
| --- | --- | --- |
| DataFrames | A table-like structure in Pandas that stores the dataset in rows and columns | Loading and working with the CSV data |
| Exception handling (`try / except`) | Catches errors so the program does not crash if the file cannot be read | Loading the dataset |
| Handling missing values | Detecting blank values and fixing them by dropping rows or filling with mean, median or mode | Cleaning the dataset |
| Removing duplicates | Finding and deleting repeated rows so each country appears once | Cleaning the dataset |
| Sorting and selecting data | Ordering rows by a column and picking the top or bottom few | Happiest and least happy countries, highest and lowest factors |
| Descriptive statistics | Summary values such as count, mean, minimum and maximum | Exploring the dataset |
| Correlation | A number between -1 and +1 showing how strongly two columns are related | Correlation analysis and heatmap |
| Data visualization | Showing data as charts to make patterns easy to see | Bar charts, scatter plots, heatmap |

---

## How to Run / Installation

### Prerequisites

- Python 3.8 or higher
- Git (to clone the repository)
- VS Code with the Python and Jupyter extensions, or Jupyter Notebook

### Steps

1. Install Python 3 from [python.org](<https://www.python.org/downloads/>).
2. Clone the repository:```
   git clone <your-repository-link>
   cd <repository-folder>
   ```
3. Install the required libraries:```
   pip install pandas matplotlib seaborn jupyter
   ```
4. Open `world_happiness.ipynb` in VS Code (with the Jupyter extension) or start Jupyter Notebook:```
   jupyter notebook
   ```
5. In the first cell, check that `file_path` points to the dataset (`happiness.csv`).
6. Run the cells from top to bottom (**Run All**, or press **Shift + Enter** on each cell).

### Notes

- Run the first cell before any other cell, because it loads the dataset that all the other cells use.
- If you restart the kernel, run the first cell again.

---

## Project Structure

```
│
├── happiness.csv      
├── main.ipynb         
└── README.md          

```

---

## Conclusion

This project shows how Python, Pandas and Jupyter Notebook can be used to load, clean, analyze and visualize a real-world dataset step by step. The notebook covers the complete data analysis process, from reading the raw CSV file to presenting the results as charts.

The results show that GDP per capita, social support and life expectancy are all positively related to a country's happiness score, and the charts make these relationships easy to see. Countries with a high score, such as Switzerland, Iceland and Denmark, also rank high on these factors, while the least happy countries rank low on them.

Through this project, the key skills of loading data, handling missing values and duplicates, sorting and selecting data, finding correlations and creating visualizations were practiced using Pandas, Matplotlib and Seaborn.

---

## Author

**\[SRIJAN KUMAR MAURYA\]**