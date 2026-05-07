# 🚀 SpaceX Falcon 9 Landing Prediction — IBM Data Science Capstone

A full end-to-end data science project completed as part of the **IBM Data Science Professional Certificate** on Coursera. The project predicts whether a SpaceX Falcon 9 first-stage booster will successfully land, which is the key factor in reducing launch costs.

## 📁 Repository Structure

```
├── Data_collection (1).ipynb     # SpaceX API data collection
├── Webscraping.ipynb             # Wikipedia web scraping for historical data
├── Data wrangling.ipynb          # Data cleaning and feature engineering
├── EDA_SQL.ipynb                 # Exploratory data analysis using SQL queries
├── EDA_DataVisualization.ipynb   # Visual EDA with matplotlib and seaborn
├── Folium.ipynb                  # Interactive launch site map using Folium
├── Classification.ipynb          # ML models and final predictions
└── spacex-dash-app.py            # Interactive Plotly Dash dashboard
```

## 🔍 Project Overview

SpaceX advertises Falcon 9 launches at \$62 million, far cheaper than competitors, largely because the first stage can be recovered and reused. This project builds a classifier to predict first-stage landing success using real launch data.

### Project Workflow

1. **Data Collection** — Fetching launch data from the SpaceX REST API
2. **Web Scraping** — Supplementing data from Wikipedia using BeautifulSoup
3. **Data Wrangling** — Handling missing values, encoding features, creating labels
4. **SQL EDA** — Running exploratory queries against the dataset
5. **Visual EDA** — Plotting relationships between features and landing outcomes
6. **Geospatial Analysis** — Mapping launch sites with Folium
7. **Classification** — Training and tuning Logistic Regression, SVM, Decision Tree, and KNN models
8. **Dashboard** — Building an interactive app to visualize results

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- pandas, NumPy, scikit-learn
- matplotlib, seaborn
- Folium (interactive maps)
- Plotly Dash (web dashboard)
- BeautifulSoup (web scraping)
- SQLite / SQL

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib seaborn folium plotly dash beautifulsoup4 requests jupyter
```

### Running the Notebooks

```bash
git clone https://github.com/Vipulav-me/Project_1.git
cd Project_1
jupyter notebook
```

### Running the Dashboard

```bash
python spacex-dash-app.py
```
Then open `http://localhost:8050` in your browser.

## 📊 Results

Multiple classifiers were trained and evaluated. The best-performing model was selected based on accuracy and F1-score on the test set. Key features influencing landing success include flight number, payload mass, orbit type, and launch site.

## 📬 Contact

GitHub: [@Vipulav-me](https://github.com/Vipulav-me)
