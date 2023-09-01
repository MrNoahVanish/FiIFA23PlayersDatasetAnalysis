# FiIFA23PlayersDatasetAnalysis
This project focuses on cleaning and transforming the FIFA 23 players dataset to ensure data accuracy and usability. By addressing issues such as data type discrepancies, separating joined date columns, converting currency columns to integers, and handling text formatting, the dataset will be prepared for further analysis.


Project Description:

The FIFA 23 Players Dataset Analysis project aims to explore and gain insights from a dataset containing information about football players featured in the FIFA 23 video game. This dataset provides a rich source of information about the attributes, performance, and characteristics of these virtual football players. The project encompasses various data processing and analysis tasks, including data filtering, cleaning, transformation, and exploratory data analysis (EDA).

About the Dataset:

The dataset used in this project is sourced from Kaggle and includes information about FIFA 23 players. It contains a wide range of attributes for each player, including their personal details, in-game statistics, club affiliation, contract information, and more. Here are some key columns in the dataset:

Name: The name of the player. Overall: The overall rating of the player in the game. Age: The age of the player. Value: The value of the player in Euros. Wage: The wage of the player in Euros. Nationality: The nationality of the player. Club Name: The name of the club the player belongs to. Contract Until: The date until which the player's contract is valid. Preferred Foot: The player's preferred foot for kicking. International Reputation: The player's international reputation. ... Data Filtering:

The project starts with data filtering, where we load the dataset and filter out unnecessary columns to focus on relevant attributes. The filtering process involves selecting columns such as 'Name,' 'Overall,' 'Age,' 'Value,' 'Wage,' 'Nationality,' 'Club Name,' 'Contract Until,' 'Preferred Foot,' 'International Reputation,' and more. These columns are selected based on their potential significance for analysis.

Data Cleaning:

Data cleaning is a crucial step in preparing the dataset for analysis. In this project, we ensure data cleanliness by addressing issues such as missing values, data type mismatches, and inconsistent formatting. Key data cleaning steps include:

Handling missing values in the 'Release Clause' column by filling them with '€0.' Ensuring appropriate data types for columns, such as converting currency columns ('Value,' 'Wage,' 'Release Clause') to integers. Separating 'Joined On' into year, month, and day columns. Removing newline characters from the 'TotalStats' column. Data Transformation:

Data transformation involves converting data into a more suitable format for analysis. Key transformation steps include:

Converting player heights from centimeters to meters (assuming the dataset already provides heights in cm). Converting player weights from kilograms to pounds (assuming the dataset already provides weights in kg). Separating 'Club Name' and 'Club Position' into distinct columns for better analysis. Creating new columns to capture additional information, such as 'Joined_Year,' 'Joined_Month,' and 'Joined_Day.' Exploratory Data Analysis (EDA):

EDA is a critical phase in understanding the dataset and uncovering valuable insights. In this project, we conduct various EDA tasks, including:

Generating summary statistics to understand the central tendencies and spreads of numeric attributes like 'Overall,' 'Age,' 'Value,' and 'Wage.' Creating distribution plots, box plots, and histograms to visualize data distributions. Constructing correlation heatmaps to explore relationships between numeric attributes. Utilizing countplots and bar plots to analyze the distribution of categorical attributes like 'Preferred Foot' and 'Nationality.' Building scatter plots to investigate relationships between attributes (e.g., 'Age' vs. 'Overall'). Using pair plots for an overview of pairwise relationships among numeric variables. Conclusion:

The FIFA 23 Players Dataset Analysis project encompasses data filtering, cleaning, transformation, and exploratory data analysis to provide insights into the attributes and characteristics of virtual football players in the game. The project's findings can be used to inform game balancing, player statistics, and overall gaming experience.

This project demonstrates the importance of data preprocessing and exploratory analysis in understanding and deriving value from a complex dataset, offering insights that can be leveraged for further analysis or decision-making in the context of the FIFA 23 video game.
