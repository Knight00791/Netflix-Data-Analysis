# 📺 Netflix Data Analysis with Python

This project dives deep into Netflix’s library of shows and movies to uncover trends, patterns, and insights related to content production, release timelines, and global distribution.

Using Python libraries like Pandas, Matplotlib, and Seaborn, the analysis answers key questions about Netflix's content and visualizes the findings.

---

## 🔍 Project Objectives

- Clean and preprocess the Netflix dataset
- Understand the distribution of TV shows vs movies
- Identify top countries contributing to Netflix content
- Analyze release trends over the years
- Explore ratings, durations, and genre diversity
- Visualize key findings with interactive and static plots

---

## 📁 Project Files

| File                        | Description                                         |
|-----------------------------|-----------------------------------------------------|
| Netflix_Data_Analysis.ipynb | Google Colab Notebook: step-by-step EDA & visuals   |
| netflix1.csv                | Raw dataset with Netflix titles metadata            |

---

## 🧰 Tools & Libraries Used

- Python 3.x
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Key Insights

- **Content Type**: More movies than TV shows in the dataset.
- **Country-wise Production**: The U.S. leads, followed by India and the UK.
- **Release Trends**: Releases surged from 2015–2020, reflecting Netflix's rapid expansion.
- **Ratings**: Most content is for mature audiences (TV-MA, TV-14).
- **Duration**: TV shows span multiple seasons; most movies run 80–120 minutes.

---

## 📂 Dataset Overview

The dataset contains fields such as:
- `type` – Movie or TV Show
- `title` – Content title
- `director` – Director(s)
- `cast` – Main cast
- `country` – Country of origin
- `date_added` – Date added to Netflix
- `release_year` – Release year
- `rating` – Age rating (e.g., TV-MA, PG)
- `duration` – Movie runtime or TV show seasons
- `listed_in` – Genres
- `description` – Short summary

---

## 🧪 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
   cd netflix-data-analysis
   ```

2. **Open the notebook in Google Colab:**
   - Upload `Netflix_Data_Analysis.ipynb` and `netflix1.csv` to your Google Drive or directly to Colab
   - [Open in Google Colab](https://colab.research.google.com/) and run the notebook step by step

3. **Install required libraries (if prompted in Colab):**
   ```python
   !pip install pandas matplotlib seaborn
   ```

---

## 📷 Sample Visualizations

*(Add screenshots or charts here to showcase your results!)*

---

## 📌 Future Enhancements

- Build interactive dashboards with Plotly or Streamlit
- Predict content success based on metadata
- Perform sentiment analysis on descriptions

---

## 🤝 Contributions

Contributions, suggestions, and issues are welcome!  
Feel free to fork this repo and submit a pull request.

---

**Happy Analyzing!**
