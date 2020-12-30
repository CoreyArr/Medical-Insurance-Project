

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
    <h3>Further Eda</h3>
    <h5>Physical Sweeper Plot of all 18 types</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/ps_barplot.png?raw=true" alt="Physical Sweeper Bar Plot">
    The Dragon, Fighting, Fire and Electric are all types that were previously identified for having high attack, high speed, or a combination of both. I want to further explore this data to see if there is a trend. Particularly types having high affinities in the features I created that comprise of stat combinations.
    <h5>Special Sweeper Plot of all 18 types</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/ss_barplot.png?raw=true" alt="Special Sweeper Bar Plot">
    The combined median values for Sp. Attack and Speed are represented here. Dragon appears once again near the top of the stack and Bug towards the bottom.
    <h5>Wall Bar Plot of all 18 types</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/wall_barplot.png?raw=true" alt="Wall Bar Plot">
    A "Wall" represents a species Health, Defense and Sp. Defense values. Dragon makes another appearance. So far we have represented all of the possible stat values and Dragon has appeared. However lets explore the two remaining arch-types for a through anaylsis.
    <h5>Physical Tank Bar Plot of all 18 types</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/pt_barplot.png?raw=true" alt="Physical Tank Bar Plot">
    Dragon again rounds out the top 5.
    <h5>Special Tank Bar Plot of all 18 types</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/st_barplot.png?raw=true" alt="Special Tank Bar Plot">
</p>
    In this last plot Dragon again rounds out the upper third of the bar plot. I collected the data based on the type placement and trends. To create a new dataframe with those findings.
    <h5>Type Plotting against Favorable and Unfavorable feature.</h5>
<img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/point_plot.png?raw=true" alt="PairGrid">
</details>

<details>
    <summary>Part 4</summary>
    <h3>Summarizing Findings</h3>
    <h4>Do pokemon types influence stat distributions ?</h4>
    <p>
    After evaluating the data and you can see that pokemon types do heavily influence stat distributions. The Development team at Game Freak heavily favorites <b>Dragon</b> type pokemon where as they do not favor <b>Bug</b> type pokemon. <b>Water</b> type they appear to be indifferent on as they have no favorable or unfavorable arch-types based on median values.
    <h4>Are those pokemon types more favorable when it comes to stat distributions</h4>
    <p>This question was an interesting one to answer as select types appear in the upper third of the stat distributions. Notably Dragon, Ice, Electric, Steel, Rock, and Fire. These types represent high stat distributions and more appearances in the favorable third, less while showing up less in the unfavorable third of the barplots. Dragon type being the only exception, being that they do not make any appearance other than in favorable. This leads me to the "balanced" types those are types that make equal appearances in both favorable and unfavorable those are, Ground, Flying, Fairy, Fighting, and Psychic. Then they're the unfavorable, those of which I believe can be explored further by the GameFreak. These types include, Poison, Normal, Grass, Bug, Ghost, and Dark. Then there is Water the only type that is neither favorable or unfavorable.</p>
    <h4>"What suggestions could be proposed from the findings on this dataset"</h4>
    <p>When exploring this data and understanding the bias, trends and distribution of data I began to look more towards the amount of pokemon released each generation.</p>
    <div>
    <img src="https://github.com/AlignedMind/Pokedex_EDA_Project/blob/master/Analysis_Images/pokedex_count.png?raw=true" alt="Pokedex Count">
    </div>
    I saw that they was a trend of rise and fall with the introduction of new species. After generation five there was a major decline and a stagnation in the number of new pokemon released. Which leads me to showcase those pokemon that have unfavorable stat distributions, this analysis showcased that types influence stats and those stats impact how well a pokemon can perform in battle. Poison, Normal, Grass, Bug, Ghost, and Dark pokemon should be more heavily focused on perhaps combining types that are unfavorable and those that are favorable.
</details>
    <details>
    <summary>Part 5</summary>
    <h3>Closing Thoughts</h3>
    <p> This project I hope can produce value for GameFreak and Nintendo when developing their next game. I seek to revisit this project and performing machine learning on the features. To perhaps predict base stat distributions on unreleased pokemon by exploring type combinations using MLR or Neural Networks to predict what stats can be increased for each type to shift them into a more favorable position, while not over powering them like dragon types have been and currently are. 
    </p>
</details>
