# 🛍️ Customer Segmentation using K-Means Clustering

This machine learning project groups customers based on **Age**, **Annual Income**, and **Spending Score** using the **K-Means Clustering algorithm**. It helps businesses understand different types of customers so they can make smarter marketing decisions.
And I made a blog post based on this . The link is given below:
https://medium.com/@jissaannjuby/boxplots-️-mall-customer-segmentation-my-first-ml-project-that-actually-made-sense-83b28207f46c
---

## 📁 Dataset

- **File Used:** `Mall_Customers.csv`
- **Key Features:**
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Libraries:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

---

## 📊 Workflow Steps (Simplified)

### 🔹 1. Load and Preprocess Data
Import the CSV file and clean the data. Convert text (like Gender) into numbers so the model can understand it.

### 🔹 2. Outlier Removal
Remove extreme values using a method called IQR (Interquartile Range) to improve clustering accuracy.

### 🔹 3. Visualize the Clean Data
Draw boxplots to make sure the data is within a healthy range and doesn't have big outliers.

### 🔹 4. Scale the Data
Standardize the values so features like income and age are treated fairly during clustering.

### 🔹 5. Use the Elbow Method
Find the best number of clusters by drawing a line graph and looking for the "elbow" point where the drop in error slows down.

### 🔹 6. Apply K-Means Clustering
Group customers into different clusters based on their features.

### 🔹 7. Visualize the Results
Plot the clusters to see how different types of customers behave based on income and spending.

---

## 📌 What You’ll Learn

- How to clean and prepare real-world data
- How to group data using clustering (unsupervised learning)
- How to visualize patterns and get business insights
- Why scaling and outlier removal matter in ML

---

## 🚀 How to Run This Project

1. Clone the repository from GitHub.
2. Open the project folder in Jupyter Notebook.
3. Install required libraries (`pandas`, `matplotlib`, etc.).
4. Run the notebook step-by-step to see results.

---

## 📁 Folder Structure


customer-segmentation-kmeans/
├── Mall_Customers.csv
├── customer_segmentation.ipynb
├── README.md
└── .gitignore
```

---

## 📂 .gitignore (to exclude unnecessary files)

```
venv/
__pycache__/
.ipynb_checkpoints/
*.pyc
.DS_Store
```

---

## 🌟 Project Output

- The project segments customers into distinct groups based on their:
  - Age
  - Annual Income
  - Spending Score
- Example: You may find clusters like:
  - High Income – Low Spending
  - Low Income – High Spending
  - Young Age – High Spending, etc.

---
```
Here's a sneak peek:

![Image](https://github.com/user-attachments/assets/9341a732-0ccc-4db2-9f86-9ab21c83bd5b)

![Image](https://github.com/user-attachments/assets/a09261c9-a56e-4554-a575-7cfc95f15ee6)

![Image](https://github.com/user-attachments/assets/365b2963-e101-46bb-aaa8-6ae97b38093e)

![Image](https://github.com/user-attachments/assets/5a9620c6-f47b-49d6-9272-69221eb36aad)



## 🧠 What You’ll Learn

- How to clean and preprocess a real-world dataset.
- How to handle categorical variables and outliers.
- How to apply K-Means Clustering in a beginner-friendly way.
- How to find the optimal number of clusters using the Elbow Method.
- How to visualize clusters using 2D scatter plots.

---

## 🚀 How to Run This Project
```
1. **Clone the Repository**
   ```
   git clone https://github.com/YOUR_USERNAME/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```

2. **Install Required Libraries**
   Make sure you have Python installed. Then install the libraries:
   ```
   pip install pandas matplotlib seaborn scikit-learn
   ```

3. **Open the Notebook**
   Use Jupyter Notebook or any IDE to open:
   ```
   customer_segmentation.ipynb
   ```

4. **Run the Code**
   Run all the cells step by step. Each cell has comments and explanations to help you understand the flow.
```
---

## 📌 Summary

This project demonstrates how unsupervised learning can help businesses understand customer behavior. By segmenting customers based on their profile, we can create targeted strategies for marketing and customer service.

---

## 📊 Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- scikit-learn (sklearn)

---

## 🌐 Contact

- 📧 Email: jissaannjuby@gmail.com  
- 🐱 GitHub: https://github.com/JissaAanJuby


---

> 💡 Feel free to fork the repo, star it, and try different ML techniques on the same dataset!
