# Zomato Data Analysis – Milestone 1

## Project Overview
This project focuses on data transformation, null value handling, insight generation, and data visualization using Python and Pandas.

The analysis uses a Zomato restaurant dataset containing information about restaurants, ratings, locations, cuisines, online ordering, table booking, and approximate costs.

## Dataset
- **Dataset:** Zomato Restaurant Dataset
- **File:** `zomato.csv`
- **Source:** Zomato restaurant listings dataset
- **Format:** CSV

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Objectives
1. Load and understand the dataset using Pandas.
2. Explore the dataset structure, columns, and data types.
3. Perform data transformation.
4. Identify and handle missing values using mean imputation wherever applicable.
5. Generate meaningful insights from the data.
6. Visualize the findings using different charts.

## Data Processing
The following operations are performed:
- Removing unnecessary columns.
- Converting rating and cost columns into numeric formats.
- Removing duplicate records.
- Handling missing numerical values using mean imputation.
- Handling missing categorical values.
- Creating additional columns for analysis.

## Data Visualization
The project includes visualizations such as:
- Top restaurant locations.
- Restaurant rating distribution.
- Online ordering analysis.
- Votes versus restaurant ratings.
- Average ratings by location.

## Project Files

| File | Description |
|---|---|
| `zomato.ipynb` | Python notebook containing the complete analysis |
| `zomato.csv` | Original Zomato dataset |
| `.gitattributes` | Git LFS tracking configuration |

## How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Open `zomato.ipynb` using Jupyter Notebook or VS Code.
4. Run the notebook cells sequentially.

## Conclusion
This project demonstrates how Python can be used to clean, transform, analyze, and visualize real-world restaurant data to generate meaningful insights.
