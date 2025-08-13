# Mall Customer Segmentation

This project performs **customer segmentation** using the Mall Customers dataset.  
We apply **K-Means Clustering** to group customers based on their **Annual Income** and **Spending Score**, and visualize the results.

## 📂 Project Contents
- `Mall_Customers.csv` → Dataset used for clustering.
- `MALL CUSTOMER SEGMENT.ipynb` → Jupyter Notebook with complete analysis and code.
- `clustering_bivariate.png` → Visualization of customer segments.
- `Clustering.csv` → Output file with assigned cluster labels.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Methodology
1. **Load Data** – Import the dataset.
2. **Data Exploration** – Understand the distribution of features.
3. **K-Means Clustering** – Identify optimal number of clusters using Elbow Method.
4. **Visualization** – Scatter plot of clusters based on spending score & income.

## 📷 Output Example
![Customer Segmentation](clustering_bivariate.png)

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mall-customer-segmentation.git
