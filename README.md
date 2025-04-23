
# FIFA Data Visualization 📊⚽

This project explores and visualizes FIFA player data using Python's data science and visualization libraries. It provides insights into player attributes, nationalities, positions, and trends through compelling static and interactive visualizations.

## 📁 Dataset Information

The dataset used is derived from FIFA player statistics, typically including:
- Player names
- Nationalities
- Positions
- Age
- Overall and potential ratings
- Club affiliations
- Physical attributes (e.g., height, weight)
- Financial data (value, wage)

> **Note:** This notebook assumes the dataset is available in the working directory (`data.csv`). Adjust paths accordingly if needed.

## 🧰 Libraries Used

The following Python libraries were used:
- `numpy` and `pandas` – data manipulation
- `matplotlib.pyplot` and `seaborn` – static visualization
- `missingno` – missing value visualization
- `datetime` – date/time handling
- `ipywidgets` – interactivity with sliders, dropdowns, etc.

All visualizations are styled using the **fivethirtyeight** theme for aesthetics.

## 📊 Data Exploration & Cleaning

Initial steps in the notebook include:
- Importing the dataset with `pandas`
- Displaying info, descriptive statistics, and null values
- Visualizing missing data using `missingno.matrix()` and `missingno.bar()`
- Dropping or imputing missing values to prepare for visualization

## 📈 Visualizations Included

Key visualizations include:
- **Top 10 Nationalities**: Most represented nationalities in the dataset.
- **Age Distribution**: Histogram of player ages.
- **Top Players by Overall Rating**: Bar chart for top-rated players.
- **Club Distribution**: Club-wise player count.
- **Correlation Heatmap**: Relationships among numerical features.
- **Position Distribution**: Player count per playing position.
- **Wage vs. Value Scatter**: Highlights financial aspects.
- **Preferred Foot & Work Rate Analysis**: Pie and bar charts.
- **Physical Attributes Distribution**: Height and weight analysis.
- **Interactive Widgets**: Dropdowns and sliders to dynamically explore data.

## 🧠 Insights

Some key insights:
- Younger players often show high potential but lower current ratings.
- Certain nationalities dominate top leagues.
- Financials such as wages and player value vary significantly with age and rating.
- Most players prefer their right foot.

## 🧪 How to Run the Notebook

To run this notebook locally:

1. Clone this repository or download the `.ipynb` file.
2. Ensure you have the necessary libraries installed:
   ```bash
   pip install numpy pandas matplotlib seaborn missingno ipywidgets
   ```
3. Launch Jupyter Notebook or JupyterLab and open the notebook:
   ```bash
   jupyter notebook
   ```
4. Run all cells sequentially to generate outputs and visualizations.

> **Note**: Make sure the data file (`data.csv`) is in the same directory as the notebook.

## 🙋 Author & Acknowledgments

This notebook was developed by Praveen Shanmuga Sundaram for data visualization practice and exploratory analysis.  
Special thanks to the creators of the [FIFA dataset](https://www.kaggle.com/datasets/devansodariya/football-fifa-2019-dataset) and the open-source community at Kaggle for providing the dataset.
