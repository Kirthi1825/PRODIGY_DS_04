# PRODIGY_DS_04 — Social Media Sentiment Analysis

## 📌 Project Overview

This project was completed as **Task 4** of my Data Science Internship at **Prodigy InfoTech**.

The objective is to analyze social media sentiment data and visualize patterns in public opinions about different topics and entities.

## 🎯 Objectives

- Explore and clean social media text data.
- Analyze Positive, Negative, Neutral, and Irrelevant sentiment categories.
- Identify the most frequently mentioned entities.
- Visualize sentiment distribution and compare sentiment patterns across entities.

## 📂 Dataset

**Dataset:** Twitter Entity Sentiment Analysis

**Source:** [Prodigy InfoTech Data Science Datasets](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%204)

The dataset contains tweet IDs, entities, sentiment labels, and tweet text.

**Columns:**
- `ID` — Tweet identifier
- `Entity` — Topic, brand, or entity associated with the tweet
- `Sentiment` — Sentiment category
- `Tweet` — Tweet text

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## ⚙️ Project Workflow

1. Loaded the Twitter training dataset.
2. Explored the dataset structure and sentiment categories.
3. Checked for missing values and duplicate records.
4. Removed rows with missing sentiment labels or tweet text.
5. Removed duplicate rows and empty tweets.
6. Visualized the overall sentiment distribution.
7. Identified the top 10 entities by tweet count.
8. Compared sentiment distributions across the top 10 entities.
9. Calculated sentiment counts and percentages.

## 📊 Sentiment Analysis Results

The cleaned dataset contained **71,484 rows and 4 columns**.

| Sentiment | Count | Percentage |
|---|---:|---:|
| Negative | 21,652 | 30.29% |
| Positive | 19,677 | 27.53% |
| Neutral | 17,651 | 24.69% |
| Irrelevant | 12,504 | 17.49% |
| **Total** | **71,484** | **100%** |

### Key Findings

- Negative sentiment was the most common category, accounting for 30.29% of the dataset.
- Positive sentiment accounted for 27.53% of the tweets.
- Neutral sentiment represented 24.69% of the dataset.
- Irrelevant sentiment was the least common category at 17.49%.

## 📈 Visualizations

The project includes:

1. **Sentiment Distribution:** Shows the number of tweets in each sentiment category.
2. **Top 10 Entities:** Displays the entities with the highest number of tweets.
3. **Sentiment by Entity:** Compares sentiment categories across the top 10 entities.

## ▶️ How to Run

1. Open `PRODIGY_DS_04.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. The dataset is loaded from the Prodigy InfoTech GitHub repository.
4. Review the cleaning steps, sentiment summary, and visualizations.

## ✅ Conclusion

This project demonstrates how Python-based data analysis and visualization can be used to explore social media sentiment. Negative sentiment was the most common category in the cleaned dataset, while Irrelevant sentiment was the least common. The visualizations also help compare tweet volumes and sentiment patterns across different entities.

## 👩‍💻 Internship Details

**Organization:** Prodigy InfoTech  
**Program:** Data Science Internship  
**Task:** Task 4 — Social Media Sentiment Analysis

#ProdigyInfoTech #DataScience #Python #SentimentAnalysis #DataVisualization
