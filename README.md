# Customer Segmentation Analysis of MixITup Using K-Prototypes

## 📌 About the Project

This project analyzes customer data from **MixITup** to understand different types of customers based on their characteristics, spending behavior, and preferences.

The project uses **customer segmentation** to group customers with similar characteristics. The **K-Prototypes clustering algorithm** is used because the dataset contains both numerical and categorical variables.

---

## 🎯 Project Objective

The main objectives of this project are to:

- Identify different customer segments
- Understand the characteristics of each customer group
- Analyze differences in income and spending behavior
- Explore customer preferences and demographics
- Generate insights that can support customer-focused business strategies

---

## 📂 Dataset

The dataset contains information about **200 customers with 10 variables**, including demographic characteristics, financial information, spending behavior, and customer preferences.

| Variable | Description |
|---|---|
| ID | Unique customer identifier |
| Gender | Customer's gender |
| Age | Customer's age |
| Income | Customer's monthly income |
| Spending Score | Customer's spending score |
| Married | Customer's marital status |
| City | Customer's city of residence |
| Promo | Customer's promotional response/category |
| Favorite Day | Customer's preferred day |
| Favorite Flavor | Customer's preferred MixITup flavor |

---

## 🔎 Data Understanding

The first step was to understand the structure and characteristics of the dataset.

The analysis included:

- Checking the number of records and variables
- Identifying numerical and categorical variables
- Checking missing values
- Checking duplicate records
- Identifying inconsistent and unusual values

The dataset initially consisted of **200 records and 10 variables**.

---

## 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared before performing the clustering analysis.

The preprocessing included:

- Handling missing values
- Cleaning inconsistent categorical values
- Handling identified data anomalies
- Preparing numerical variables
- Preparing categorical variables

The cleaned dataset was then used as input for the clustering process.

---

## 📊 Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand customer characteristics and identify patterns within the data.

The analysis explored:

- Age
- Monthly income
- Spending score
- Gender
- Marital status
- City
- Promotional response
- Favorite day
- Favorite flavor

Various statistical summaries and visualizations were used to compare customer characteristics.

---

## 🤖 Customer Segmentation

The **K-Prototypes** algorithm was used to group customers based on similarities across numerical and categorical variables.

Different numbers of clusters were evaluated before selecting **4 clusters** for the final analysis.

The customers were divided into:

- Cluster 0
- Cluster 1
- Cluster 2
- Cluster 3

> Cluster numbers are only labels assigned by the algorithm and do not represent a ranking or indicate that one cluster is better than another.

---

## 📈 Cluster Analysis & Results

After clustering, each segment was analyzed using both numerical and categorical variables.

### Cluster 0

Customers in this cluster generally have:

- Age around 20–60 years
- Monthly income around Rp20–50 million
- Relatively low spending scores
- More male customers
- A majority of unmarried customers
- Many customers from Tangerang

### Cluster 1

Customers in this cluster generally have:

- Age around 20–40 years
- Monthly income around Rp0–20 million
- Moderate to high spending scores
- More female customers
- Many customers from Jakarta

### Cluster 2

Customers in this cluster generally have:

- Age around 40–60 years
- Monthly income around Rp0–20 million
- Low to moderate spending scores
- More female customers
- Many customers from Jakarta

### Cluster 3

Customers in this cluster generally have:

- Age around 25–40 years
- Monthly income around Rp20–50 million
- High spending scores
- More female customers
- Many customers from Depok

---

## 💡 Key Insights

The clustering analysis shows that MixITup customers can be divided into **four distinct segments** with different combinations of demographic, financial, behavioral, and preference characteristics.

The main differences between the segments can be observed in:

- Monthly income
- Spending behavior
- Age
- City
- Gender
- Promotional response
- Favorite day
- Favorite flavor

The combination of numerical and categorical variables provides a more complete understanding of the characteristics of each customer segment.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- K-Prototypes
- Google Colab

---

## 🔄 Project Workflow

```text
Customer Data
      ↓
Data Understanding
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
K-Prototypes Clustering
      ↓
4 Customer Segments
      ↓
Cluster Analysis
      ↓
Customer Insights
