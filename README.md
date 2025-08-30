# <img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/aad8f67d-15bb-412c-8df5-d87818214da5" /> Netflix Movie Data Analysis Project    <img width="22" height="22" alt="image" src="https://github.com/user-attachments/assets/aad8f67d-15bb-412c-8df5-d87818214da5" />


## 🎥Introduction 🎥



This project focuses on analyzing Netflix movie data using Python to uncover insights about genres, popularity, voting patterns, and release trends. The analysis aims to highlight patterns in Netflix’s movie collection and provide a better understanding of audience preferences. Netflix is one of the largest streaming platforms worldwide, offering a vast collection of movies and shows across multiple genres. With thousands of titles available, data analysis plays a crucial role in understanding viewer preferences, identifying popular genres, and improving recommendation systems.

This project focuses on analyzing a dataset of Netflix movies to uncover trends, popularity patterns, and insights that can help in better decision-making and content strategy.

---

## 📊 Project Overview

The dataset contains information about **9,838 movies** available on Netflix. Initially, the dataset had multiple columns including descriptions and poster URLs. After **data preprocessing and cleaning**, only the most relevant columns were kept for analysis.

The goal of this project is to study Netflix’s movie trends and answer key business questions such as:

* Which genres are most frequent on Netflix?
* Which movies are the most and least popular?
* Which year had the highest number of movies filmed?

---

## 🎯 Objectives

The main objective of this project is to analyze Netflix movie data and extract useful insights. The analysis is focused on answering the following key questions:

* What is the most frequent genre of movies released on Netflix?

* Which genres have received the highest votes?

* Which movie has the highest popularity and what is its genre?

* Which movie has the lowest popularity and what is its genre?

* Which year has the highest number of movies filmed?

## 🗃️ Dataset Used

The original dataset contained **9 columns**:

* `Release_Date`
* `Title`
* `Overview`
* `Popularity`
* `Vote_Count`
* `Vote_Average`
* `Original_Language`
* `Genre`
* `Poster_Url`

  🎥 **Total Rows:** 9,838

After preprocessing, the dataset was reduced to **6 important columns**:

* `Release_Date`
* `Title`
* `Popularity`
* `Vote_Count`
* `Vote_Average`
* `Genre`

  🎥 **Total Rows after Preprocessing:** 25552 

---

## 🛠️ Tools & Technologies

* **Python** – Data analysis
* **Pandas, NumPy** – Data cleaning and transformation
* **Matplotlib, Seaborn** – Data visualization
* **Jupyter Notebook / Google Colab** – Development environment

---

## 📈 Analysis Performed

* Genre frequency analysis
* Highest and lowest popularity movies
* Vote count and average rating analysis
* Year-wise movie trend analysis

---

### 📷 Screenshots

1. What is the most frequent genre of movies released on Netflix?


    <img width="750" height="500" alt="image" src="https://github.com/user-attachments/assets/ae8d3c9b-b66b-4dcc-8330-c3dc5f4bda53" />


3. Which genres have received the highest votes?

   <img width="750" height="500" alt="image" src="https://github.com/user-attachments/assets/638cba8b-a111-426e-9db4-c26ad7054bfe" />


5. Which movie has the highest popularity and what is its genre?

   <img width="783" height="215" alt="image" src="https://github.com/user-attachments/assets/7a89fb03-9b2c-4847-870a-0ceff7799548" />


7. Which movie has the lowest popularity and what is its genre?

   <img width="878" height="307" alt="image" src="https://github.com/user-attachments/assets/a60cf55f-9637-4eff-92db-0d4ab806cfba" />


9. Which year has the highest number of movies filmed?

   <img width="726" height="645" alt="image" src="https://github.com/user-attachments/assets/038c730c-fe43-4f9f-b9c0-100c3676dd46" />


##  Key Insights

* Certain genres dominate Netflix’s library, making them the most frequently released categories.
* Some movies gained extremely high popularity, while a few remained unnoticed despite being on the platform.
* Voting patterns reveal audience preferences across different genres.
* The dataset highlights peak years when a large number of movies were filmed and added.

---

## 🚀 How to Run

1. Clone this repository or download the project files.

2. Make sure Python (3.8 or above) is installed on your system.

3. Open the project in **Jupyter Notebook** or **Google Colab**.

4. Import the required libraries in your notebook:

   ```python
   import numpy as np
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns
   ```

5. If any of these libraries are not installed, install them using the following commands:

   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

6. Load the dataset (`mymoviedb.csv`) into your notebook:

   ```python
   df = pd.read_csv("mymoviedb.csv")
   ```

7. Run the analysis cells to generate insights and visualizations.

---


## Summary

Q1: What is the most frequent genre in the dataset?
Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.

Q2: What genres has highest votes?
we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movies

Q3: What movie got the highest popularity? what's its genre?
Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action, Adventure and Science Fiction.

Q3: What movie got the lowest popularity? what's its genre?
The united states, thread' has the highest lowest rate in our dataset and it has genres of music, drama, 'war', 'sci-fi' and history`.

Q4: Which year has the most filmed movies?
year 2020 has the highest filming rate in our dataset.

## 🙋‍♀️ Author

**Shreya Nandkumar Thaware**
📧 [shreyathaware9@gmail.com](mailto:shreyathaware9@gmail.com)
🔗 [LinkedIn Profile](https://www.linkedin.com/in/shreya-thaware-b9a006254)
🌐 [Portfolio](https://www.datascienceportfol.io/shreyathaware9)
