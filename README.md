# Netflix Data Analysis: Content Trends (VOIS AICTE Project)

This repository contains the Python code, dataset, and documentation for a Netflix content analysis project, completed as part of the VOIS AICTE Internship program (October 2025).

# Project Overview

The goal of this project is to analyze the Netflix dataset (`Netflix Dataset (1).csv`) to understand trends in its content catalog. The analysis focuses on the distribution of movies versus TV shows, popular genres, and the geographical diversity of content over time. The findings aim to provide strategic insights for Netflix's content acquisition and production strategies.

# Problem Statement

The core problem addressed is 'Content Trends Analysis for Strategic Recommendations'. Specifically, the analysis aims to:

1 Analyze the distribution and growth of Movies vs. TV Shows added to Netflix over the years.
2 Identify the most frequent genres and observe changes in their popularity over time.
3 Compare country-wise contributions to assess the global diversity of Netflix's content library.
4 Provide data-driven recommendations for future content strategy.

# Dataset

* **File:** `Netflix Dataset (1).csv`
* **Description:** This dataset contains information about TV shows and movies available on Netflix, including details like title, director, cast, country, release date, rating, duration, type (genre), and description.

# Technologies Used

* **Language:** Python
* **Libraries:**
    * Pandas (for data manipulation and analysis)
    * Numpy (for numerical operations)
    * Matplotlib (for static visualizations)
    * Seaborn (for enhanced static visualizations)
    * Plotly Express (for interactive visualizations like the map)
* **Environment:** Google Colab / Jupyter Notebook

# Files in this Repository

* `Netflix_Analysis 2.ipynb`: The Jupyter Notebook containing the Python code for data cleaning, analysis, and visualization.
* `Netflix Dataset (1).csv`: The raw dataset used for the analysis.
* `README.md`: This file, explaining the project.
* *(Optional: You can also add the `.pptx` file here if you wish)* `[Your Name]_Netflix Data Analysis Project PPT 3.pptx`

# How to Run

1.  Ensure you have Python and the necessary libraries installed (or use Google Colab).
2.  Download the `.ipynb` notebook and the `.csv` dataset file.
3.  Place the `.csv` file in the same directory as the notebook, or upload it to your Google Colab session.
4.  Open the notebook using Jupyter Notebook or Google Colab.
5.  Run the cells sequentially to perform the analysis and generate visualizations.

# Key Visualizations Generated

* Line chart showing the trend of Movies vs. TV Shows added per year.
* Bar chart displaying the Top 10 genres.
* Stacked bar chart comparing Movie vs. TV Show counts for the Top 10 countries.
* Interactive Choropleth map illustrating the global distribution of content.
* Line chart tracking the popularity trends of the Top 5 genres over time.
