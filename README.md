# Data Visualization and Manipulation

This repository contains Python scripts showcasing various data visualization and manipulation techniques using popular libraries such as Pandas, Matplotlib, and Scikit-learn. The examples are divided into two main parts:

## Part 1: Data Visualization

This section demonstrates how to visualize data using scatter plots, regression lines, polynomial regression, and line charts.

### Dataset 1: Tips Dataset
#### Scatter Plot
- Visualizes the relationship between `total_bill` and `tip`.

#### Linear Regression
- Fits a linear regression model to predict tips based on total bills.
- Displays the regression line alongside the scatter plot of actual data points.

#### Polynomial Regression
- Demonstrates the use of polynomial regression to model complex relationships (example dataset: `Position_Salaries.csv`).
- Visualizes predicted and actual data.

### Line Chart
- Illustrates how to connect data points using a line chart for simple visualization.

## Part 2: Data Manipulation

This section focuses on data exploration and manipulation using the flights dataset.

### Dataset 2: Flights Dataset
- Examines flight details including departure, arrival times, delays, and distances.

#### Key Operations
1. **Data Exploration:**
   - Display top rows of the dataset.
   - Generate summary statistics for numerical columns using `.describe()`.
   - Analyze the distribution of flights per month using `.groupby()`.

2. **Distance Binning:**
   - Segments flight distances into intervals (e.g., every 1000 miles) for analysis.

## How to Use

### Prerequisites
Ensure you have the following Python libraries installed:
- pandas
- matplotlib
- scikit-learn

Install them using pip:
```bash
pip install pandas matplotlib scikit-learn
```

## File Structure
- `tips.csv`: Contains data on restaurant bills and tips.
- `Position_Salaries.csv`: Example dataset for polynomial regression.
- `flights.csv`: Flight details including delays and distances.
- `data_visualization.py`: Visualization examples.
- `data_manipulation.py`: Data manipulation examples.

## Output
The scripts generate visualizations such as scatter plots, regression lines, and line charts, along with detailed data exploration outputs.

## License
This project is licensed under the MIT License. Feel free to use and modify the code as needed.

---
### Author
Md. Monowarul Amin | [Linked in](https://www.linkedin.com/in/md-monowarul-amin-a673a0203/)
