# 🏠 Airbnb NYC 2024 – Exploratory Data Analysis (EDA)

A data analysis project that explores the Airbnb listings in New York City for 2024. The project involves deep analysis, visualization, and insights from the dataset to understand patterns in pricing, availability, and host behavior.

---

## 📁 Dataset

- **Name**: `new_york_listings_2024.csv`
- **Source**: Airbnb (Kaggle or Inside Airbnb)
- **Shape**: ~49,000 rows × 18 columns
- **Columns** include:
  - `name`, `host_name`, `neighbourhood_group`, `room_type`, `price`, `minimum_nights`, `number_of_reviews`, `availability_365`, etc.

---

## 🎯 Objective

To uncover key trends and insights from the NYC Airbnb dataset by using data cleaning, statistical analysis, and visualizations. Focus areas include:

- Popular room types and areas
- Price distribution
- Host activity levels
- Review patterns
- Feature correlation

---

## 🛠️ Tools & Technologies

- Python 🐍
- Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn

---

## 🔍 EDA Highlights

- ✅ Cleaned missing and invalid data
- ✅ Plotted histograms of price, minimum nights, number of reviews
- ✅ Bar plots for room type, neighbourhood group, etc.
- ✅ Correlation heatmap of numerical features
- ✅ Removed outliers for better visualization

---

## 📊 Visual Examples

### 🔹 Price Distribution by Room Type
```python
sns.boxplot(x='room_type', y='price', data=df)
