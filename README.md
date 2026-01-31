# 🍕 Food Delivery Data Integration & Analysis

This project is a complete data analysis workflow that combines data from three different sources to uncover business insights for a food delivery service.

---

## 📂 Project Structure
To keep things organized, the repository includes:
* **`orders.csv`**: Transactional data (order IDs, dates, and amounts).
* **`users.json`**: Customer profiles (names, cities, and membership types).
* **`restaurants.sql`**: Master list of restaurants, cuisines, and ratings.
* **`Food_Delivery_Analysis.ipynb`**: The main Google Colab notebook containing the Python code.

---

## 🚀 How to Run the Analysis
Setting this up is simple and doesn't require any software installation:

1. **Open Google Colab**: Go to [colab.research.google.com](https://colab.research.google.com).
2. **Upload the Notebook**: Import the `.ipynb` file from this repository.
3. **Upload the Data**: 
   * Click the **Folder icon** on the left sidebar in Colab.
   * Upload `orders.csv`, `users.json`, and `restaurants.sql`.
4. **Run All**: Click `Runtime` > `Run all` to see the results.

---

## 📊 Key Insights Found
Through the merged dataset, we identified several trends:
* **Gold Members**: They account for **50%** of all orders.
* **Top City**: **Chennai** is the highest revenue-generating city for Gold members.
* **Best Cuisine**: **Mexican** food has the highest Average Order Value.
* **Quality**: **3,374 orders** were placed at restaurants with a rating of **4.5 or higher**.
* **Busiest Time**: Revenue peaks during the **3rd Quarter (Q3)**.

---

## 🛠️ Tools Used
* **Python**: For data logic.
* **Pandas**: For merging CSV and JSON files.
* **SQLite3**: For processing the SQL restaurant data.
* **Matplotlib/Seaborn**: For creating the trend charts.
