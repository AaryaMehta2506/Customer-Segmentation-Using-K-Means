Data Analytics Beginners Project
# Customer Segmentation using K-Means Clustering
In this project, we explore customer behavior patterns by clustering mall customers into distinct groups based on their income and spending habits. Using K-Means clustering, we uncover valuable insights to support smarter business decisions.

## 🎯 Project Objective

The goal is to:
- Segment customers into distinct groups (clusters)
- Understand their spending behavior
- Help businesses identify target audiences and improve marketing

---

## 📂 Dataset
**Source**: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## What is K-Means?

**K-Means** is a clustering algorithm that groups similar data points into `k` clusters based on their features.

### How it works:
1. Choose number of clusters `k`
2. Assign initial centroids randomly
3. Assign each point to the nearest centroid
4. Recalculate centroids based on current members
5. Repeat until clusters don’t change

---

## Clustering Features

We used:
- **Annual Income**
- **Spending Score**

These two features effectively describe customer purchasing power and behavior.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## Visualizations

- Elbow Method to find optimal `k`
- Scatter plot of clusters
- Cluster-wise income and spending profiles

---

## Results

After applying K-Means with `k = 5`, the customers were segmented into 5 distinct groups such as:
- **High Income, High Spending** (ideal targets)
- **Low Income, High Spending** (potentially impulsive)
- **High Income, Low Spending** (cautious buyers)
- **Low Income, Low Spending** (budget shoppers)
- **Average shoppers** (mid-market)

---

## Files

- `Mall_Customers.csv` — dataset
- `customer_segmentation.ipynb` — Jupyter Notebook with full analysis
- `requirements.txt` - libaries
- `README.md` — this file

---

## Future Improvements

- Add Age and Gender into segmentation
- Create an interactive dashboard using Streamlit or Power BI
- Use more advanced clustering algorithms like DBSCAN or Hierarchical Clustering

---

## 🤝 Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

## 👩‍💻 Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)
