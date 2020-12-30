

# *Medical Insurance Exploratory Data Analysis EDA*

## Project Goals 

- Explore data set to discover trends, anomalies, and correlations to rates.
- Clean and optimize data set for visualizations and machine learning.
- Create clear and insightful visualizations to describe and showcase findings.



## Table of Contents

<details>
    <summary>Open</summary>

        1. File Descriptions
        2. Technologies Used
        3. Executive Summary

</details>

## File Descriptions

<details>
    <summary>Open</summary>

- insurance.csv: data pre-clean
- Medical Insurance Project.ipynb: Jupyter Notebook on data analysis

</details>

## Technologies Utilized

<details>
    <summary>Open</summary>

        1. Python3
        2. Pandas
        3. Matplotlib
        4. Seaborn
        5. Sci-py
        6. Numpy
        7. sci-kit learn
</details>

 ## Executive Summary

### Webscraping Beautiful Soup
<details>
    <summary>Open</summary>
    <h3>Data Cleaning</h3>
    <h4>Primary Goal</h4>
    <p>The goals I set out for in this project was to collaborate with data scientist, Jeremy Cruzado on a portfolio piece that showcases a range of our knowledge and ability. Futhermore I set out to create value for those who are interested in investing into medical insurance, helping them understand the variables and features that contribute to the pricing model. This is a high level overview and not specific to one company or a one solution that speaks for all companies. </p>
  

### Library Imports
<details>
    <summary>Part 1</summary>
    <h3>Importing required libraries and loading into dataframe</h3>
    <p>The required libraries included the utilization of primarily pandas, numpy, matplotlibi, and seaborn. The inclusion of sklearn was for preprocessing.</p>

</details>

<details>
    <summary>Part 2</summary>
    <h3>Early EDA</h3>
    <p>This portion focused primarily on understanding the key statistics and evaluation of the dataframe. These findings were as follows:
    <h5>Max Values</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/attack_violin.png?raw=true" alt="Attack Violin Plot">
    The max values represent the highest values in each feature.
    <h5>Min Values</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/speed_violin.png?raw=true" alt="Speed Violin Plot">
    The min values represent the lowest values in each feature.
    <h5>Average Values</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/speed_violin.png?raw=true" alt="Speed Violin Plot">
    The average values represent the averages of all the values in each feature.
</details>
<details>
    <summary>Part 3</summary>
    <h3>Data Visualizations</h3>
    <h5>Histogram: BMI </h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/HistBMI.png?raw=true" alt="Histogram: BMI">
   ---
    <h5>Histogram: Charges</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/HistCharges.png?raw=true" alt="Histogram: Charges">
    ---
    <h5>Histogram: Age</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/HistAge.png?raw=true" alt="Histogram: Age">
   ---
    <h5>Histogram: Children</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/HistChildren.png?raw=true" alt="Histogram: Children">
    ---
    <h5>Heatmap: Correlation</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/Heatmap.png?raw=true" alt="Heatmap: Correlation">
</p>
    ---
    <h5>Category Side by Side Bar Plot</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/Bar.png?raw=true" alt="Category Side by Side Bar Plot">
</p>
    ---
     <h5>Scatterplot: Regressors</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/Scatter.png?raw=true" alt="Scatterplot: Regressors">
</p>
    Clear trend lines indicate that the bottom line represents non-smokers with low bmi.
    The middle group shows smokers and non-smoker with generally low bmi.
    The top trend line represents smokers with high bmi.
</details>

<details>
    <summary>Part 4</summary>
    <h3>Summarizing Findings</h3>
    <h4>Who pays more in medical insurance and why?</h4>
    <p>
        Smoker carry the highest correlates inflation to price at .78. The age variable is the second highest key factor that correlates to charges at .29, while bmi has a .19 correlation, rounding off the top 3 feaetures. Given these features, there is a clear pattern that indicates that the older and heavier you are increases the medical insurance charges. Smoking causes a substantial increase to an individuals charges. However, on average, females that do not smoke are charged more than males that do not smoke, while males that smoke are charged more than females that smoke.</p>
    <div>
    <img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/pokedex_count.png?raw=true" alt="Pokedex Count">
    </div>
</details>
    <details>
    <summary>Part 5</summary>
    <h3>Closing Thoughts</h3>
    <p> This project is the first part of a whole. The next portion will serve as a machine learniing project that utilizes ensemble learning to predict chaarges based on the present features of this data set. 
    </p>
</details>
