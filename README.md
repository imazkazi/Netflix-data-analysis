# 🎬 Netflix Data Analysis Project

This is a data analysis project focused on exploring and visualizing trends in the Netflix catalog using Python and Jupyter Notebook. The dataset includes thousands of movies and TV shows available on Netflix, providing valuable insights into content type, release trends, country distribution, and more.

---

## 📌 Project Overview

The goal of this project is to:

- Perform exploratory data analysis (EDA) on Netflix content.
- Clean and preprocess the data.
- Identify patterns and trends in the content based on factors like year, genre, type, rating, and country.
- Generate visualizations that help understand the data in a meaningful way.

---


![netflix image](https://github.com/user-attachments/assets/0974cc56-3151-447e-b816-80341f4c0ed3)


## 🗃 Dataset

**File:** `mymoviedb.csv`

The dataset contains the following features:

- `show_id` – Unique ID for every show
- `type` – Movie or TV Show
- `title` – Title of the content
- `director` – Director of the show
- `cast` – Cast members
- `country` – Country of production
- `date_added` – Date added to Netflix
- `release_year` – Year of release
- `rating` – Age rating
- `duration` – Duration (in minutes or number of seasons)
- `listed_in` – Genre categories
- `description` – Short description

---

## 📒 Notebook

**File:** `NETFLIX_data_analysis.ipynb`

This Jupyter Notebook contains:

- Data cleaning & preprocessing
- Handling missing values
- Filtering and grouping data
- Aggregation and value counts
- Visualizations with Matplotlib & Seaborn
- Insights and summary

---

## 🔍 Key Analysis Performed

- 📊 Count of Movies vs TV Shows
- 🌍 Top countries with the most content
- 📅 Trend of content added over the years
- 🔞 Distribution of content by rating
- ⏱ Average duration of movies and shows
- 🎭 Analysis of genre and category types
- 🎬 Most frequent directors and cast members

---

## 💡 Insights Gained

- Netflix has more movies than TV shows.
- The USA and India are among the top content-producing countries.
- A large portion of content was added in the past 5 years.
- TV Shows tend to have fewer entries compared to Movies.
- Certain genres and ratings dominate the catalog.

---

## 📈 Technologies Used

| Tool          | Purpose                         |
|---------------|----------------------------------|
| Python        | Programming Language             |
| Jupyter Notebook | Interactive coding and analysis |
| Pandas        | Data manipulation & analysis     |
| Matplotlib    | Data visualization               |
| Seaborn       | Advanced visualization           |
| NumPy         | Numerical operations             |

---

## ⚙️ How to Run the Project

### Prerequisites:
Make sure you have the following installed:

- Python 3.8+
- Jupyter Notebook or VS Code
- pip package manager

### Step-by-step Setup:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
