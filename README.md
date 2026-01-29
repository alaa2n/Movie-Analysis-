🎬 Movie Dataset Analysis – Data Cleaning & Exploratory Data Analysis (EDA)

This project performs a complete exploratory data analysis (EDA) on a Movies dataset containing over 7,000 records.
It includes data cleaning, transformation, statistical analysis, and multiple visualizations to uncover trends in movie performance, ratings, and industry patterns.

📌 Project Objectives

Clean and preprocess the raw movie dataset

Handle missing values, duplicates, and inconsistent fields

Explore relationships between key variables

Visualize distribution of ratings, scores, genres, and financial performance

Identify important insights such as profitable movies and director performance

🧹 1. Data Cleaning

The raw dataset contained missing values, duplicates, and mixed data types.
Cleaning steps included:

Removing duplicated rows

Filling missing categorical values using "Unknown"

Filling missing numerical values using median

Creating new features such as:

profit = gross – budget

📊 2. Exploratory Data Analysis

Various analyses were performed to understand the data:

✔ Genre Distribution

Shows which genres dominate the dataset.

✔ Rating Distribution

A bar chart illustrating how movies are distributed across age ratings (G, PG, PG-13, R, etc.)

✔ Score Distribution

Histogram showing how movies are rated by viewers, including a vertical line highlighting the average score.

✔ Budget vs. Gross Correlation

Correlation analysis (Pearson, Spearman, Kendall) to understand financial relationships.

✔ Profitability

Top 10 movies with the highest profit were identified.

✔ Director Performance

Directors were ranked based on:

Average movie score

Number of movies produced

📈 3. Visualizations Included

The project includes professional matplotlib charts:

📌 Pie Chart – Movie rating distribution

📌 Histogram – Score distribution with mean indicator

📌 Bar Chart – Genre distribution

📌 Line Chart – Runtime and score trends over the years

📌 Scatter Plot – Budget vs. gross earnings

All plots follow data-analysis best practices (clear labels, readable axes, no unnecessary styling).

🔍 4. Key Insights

There is a strong positive relationship between budget and gross revenue.

Most movies score between 6.0 and 7.5.

Certain genres (e.g., Drama, Comedy) dominate the dataset.

Ratings such as R and PG-13 are the most common.

A few directors consistently produce higher-scoring movies.

🛠 Technologies Used

Python

Pandas – data cleaning & manipulation

NumPy – numerical processing

Matplotlib – visualizations

Jupyter Notebook – documentation & workflow
