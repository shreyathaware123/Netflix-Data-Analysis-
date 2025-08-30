# 🎬 Netflix Movie Data Analysis Project

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

What is the most frequent genre of movies released on Netflix?

Which genres have received the highest votes?

Which movie has the highest popularity and what is its genre?

Which movie has the lowest popularity and what is its genre?

Which year has the highest number of movies filmed?

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

  📌 **Total Rows:** 9,838

After preprocessing, the dataset was reduced to **6 important columns**:

* `Release_Date`
* `Title`
* `Popularity`
* `Vote_Count`
* `Vote_Average`
* `Genre`

  📌 **Total Rows after Preprocessing:** 25552 

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

## 📷 Screenshots

### 1. Genre Frequency

![Genre Frequency](images/genre_frequency.png)
*Most frequent genres released on Netflix*

### 2. Popularity Trends

![Popularity Trend](images/popularity_trend.png)
*Highest and lowest popularity movies*

### 3. Yearly Trends

![Yearly Trends](images/yearly_trends.png)
*Number of movies released per year*

---

## 🧠 Key Insights

* Certain genres dominate Netflix’s library, making them the most frequently released categories.
* Some movies gained extremely high popularity, while a few remained unnoticed despite being on the platform.
* Voting patterns reveal audience preferences across different genres.
* The dataset highlights peak years when a large number of movies were filmed and added.

---

## 🚀 How to Run

1. Clone this repository.
2. Install the required Python libraries using:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook or Colab file.
4. Run the analysis cells to reproduce the results.
5. View the generated visualizations in the `images/` folder.

---

## 🙋‍♀️ Author

**Shreya Nandkumar Thaware**
📧 [shreyathaware9@gmail.com](mailto:shreyathaware9@gmail.com)
🔗 [LinkedIn Profile](https://www.linkedin.com/in/shreya-thaware-b9a006254)
🌐 [Portfolio](https://www.datascienceportfol.io/shreyathaware9)
