COVID-19 Global Data Analysis
This project analyzes the relationship between GDP per capita and COVID-19 infection rates using real-world data. The analysis includes data preprocessing, visualization, and interpretation using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

 File Structure
COVID_19.ipynb – Main Jupyter Notebook file containing the entire analysis pipeline.

 Objectives
Load and clean COVID-19 and world economic data.

Derive useful features such as maximum infection rate per country.

Visualize the relationship between economic indicators and infection rates.

Use log transformation to handle skewed infection data.

Draw scatter plots and regression plots to show correlations.

Technologies Used
Python 

Jupyter Notebook 

Pandas 

NumPy 

Seaborn 

Matplotlib 

Key Features
Maximum infection rate analysis per country.

Visualization using scatter plots and log transformations.

Correlation insights between GDP and infection rate.

Sample Plot
The key plot in this notebook:

python
Copy
Edit
x = data["GDP per capita"]
y = data["Max_infection_rates"]
sns.scatterplot(x=x, y=np.log(y))

How to Run
Clone the repository or download the notebook.

Make sure you have Python 3.x and Jupyter installed.

Install required libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Open the notebook in Jupyter:

bash
Copy
Edit
jupyter notebook COVID_19.ipynb
