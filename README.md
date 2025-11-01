
## 🎬 Netflix Movie Data Analysis

This project focuses on analyzing the **Netflix Movie Dataset** to uncover patterns, trends, and insights about genres, ratings, and movie popularity.  
The analysis involves **data cleaning, visualization, and exploration** using Python libraries like Pandas, Matplotlib, and Seaborn.

---

## 📁 Dataset Overview

The dataset contains detailed information about Netflix movies, including:
- **Title**
- **Overview**
- **Genre**
- **Release Date**
- **Popularity**
- **Vote Count**
- **Vote Average**
- **Poster URL**
- **Original Language**

---

## 🧹 Data Cleaning Process

### ✅ Removed Unnecessary Columns
- `overview`  
- `original_title`  
- `poster_url`

### ⚠️ Issues Found & Fixed
| Issue | Description | Solution |
|-------|--------------|-----------|
| Genre column | Comma-separated values and extra white spaces | Split and cleaned values |
| Release date | Stored as object | Converted to datetime |
| Vote count | Stored as object | Converted to integer |
| Vote average | Stored as object | Converted to float |

### 🕳️ Null Values
| Columns | Missing Values | Action Taken |
|----------|----------------|---------------|
| title, overview | 9 | Filled / Dropped based on context |
| popularity, vote_count, vote_average, original_language | 10 | Replaced with mean or mode |
| genre, poster_url | 11 | Cleaned and handled appropriately |

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Visualizations Performed
- **Genre Distribution** — most common genres in Netflix movies  
- **Vote Average Distribution** — how ratings are spread among movies  
- **Release Year Analysis** — number of movies released each year  

---

## 🧠 Insights & Conclusions

| Question | Answer |
|-----------|---------|
| **Q1:** What is the most frequent genre in the dataset? | 🎭 *Drama* is the most frequent genre, appearing in over **14%** of all movies. |
| **Q2:** Which genre has the highest votes? | *Drama* again leads, holding over **18.5%** of all highly voted movies (out of 25.5% popular ones). |
| **Q3:** What movie got the lowest popularity and its genre? | *The United States Thread* — Genre: *Music, Drama, War, Sci-Fi*. |
| **Q4:** Which year has the most filmed movies? | The year **2020** recorded the **highest number of films** in the dataset. |

---

## 🧩 Tools & Technologies Used
- **Python** 🐍  
- **Pandas** – Data cleaning & manipulation  
- **Matplotlib / Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis  
- *(Optional)* **Tableau** – Future dashboard visualization  

---

## 🚀 Future Work
- Build an **interactive dashboard** using Tableau or Power BI  
- Perform **sentiment analysis** on movie overviews  
- Predict **movie popularity** based on genre and release year  

---

## 👨‍💻 Author
**Himanshu Jaiswal**  
Data Scientist | Machine Learning Enthusiast  
📧 [jaiswalaasish00@gmail.com](mailto:jaiswalaasish00@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/himanshu-jaiswal1) | [GitHub](https://github.com/himanshujaiswal93)

---

⭐ *If you like this project, give it a star on GitHub!*
