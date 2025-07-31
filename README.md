# 🚢 Titanic Data Visualization & Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![seaborn](https://img.shields.io/badge/seaborn-0.11%2B-blue?logo=seaborn)
![pandas](https://img.shields.io/badge/pandas-1.3%2B-yellow?logo=pandas)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)


> A visual exploration of the Titanic dataset using Python, `pandas`, `seaborn`, and `matplotlib`  
> Highlights survival patterns by sex, class, age group, and correlations.

---

## ✨ Features

- Loads Titanic dataset directly from `seaborn`
- Cleans missing values in:
  - `age` (filled with median)
  - `embarked` (filled with mode)
- Drops less relevant columns (`who`, `deck`, `alive`, `alone`)
- Generates key visualizations:
  - Count of passengers by survival
  - Survival rate by sex
  - Survival rate by passenger class
  - Age distribution histogram
  - Survival rate by age groups
  - Correlation heatmap

---

## 📦 Requirements

- Python 3.8+
- pandas
- seaborn
- matplotlib

Install dependencies:
```bash
pip install pandas seaborn matplotlib
```

▶️ How to Run
1. Save the script as ```titanic_visualization.py.```

2. Run the script:
```
python titanic_visualization.py
```

3. View the plots in pop-up windows and check printed console messages for each plot.

## 🧠 How It Works
- Loads Titanic dataset from seaborn

- Cleans and preprocesses data

- Creates age groups using pd.cut

- Uses seaborn to plot:

   - countplot

   - barplot

   - histplot

   - heatmap

- Displays plots in sequence with descriptive titles

## 📊 Example Plots

### Survival Count

<img width="665" height="482" alt="Screenshot 2025-07-31 093402" src="https://github.com/user-attachments/assets/ea0628d5-972b-4484-a00e-86145d9d1526" />

### Survival Rate by Age, Passenger Class

<img width="902" height="674" alt="Screenshot 2025-07-31 093427" src="https://github.com/user-attachments/assets/62d67d97-9994-4415-9e3e-693ed010423c" />

<img width="773" height="480" alt="Screenshot 2025-07-31 093410" src="https://github.com/user-attachments/assets/468a9671-b550-49fc-ae63-fadeb12fec18" />

### Correlation Matrix

<img width="850" height="718" alt="Screenshot 2025-07-31 093442" src="https://github.com/user-attachments/assets/1f9def56-70e0-43de-89e5-ba00c51bb1c1" />

### Age Distribution of Passengers

<img width="889" height="666" alt="Screenshot 2025-07-31 093419" src="https://github.com/user-attachments/assets/b25881a5-5765-4257-af17-680ba2cbe257" />

## ✏️ Author

Built and documented by [nandhini1424](https://github.com/nandhini1424)
