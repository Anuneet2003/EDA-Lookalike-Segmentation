# EDA-Lookalike-Segmentation (Customer Analytics Project)
Comprehensive customer analytics project featuring exploratory data analysis, lookalike modeling, and customer segmentation using clustering techniques. Includes detailed visualizations, clustering metrics (Davies-Bouldin Index), and a PDF report of insights and results.
This repository contains a comprehensive customer analytics project, including exploratory data analysis (EDA), lookalike modeling, and customer segmentation using clustering techniques. The project leverages customer, transaction, and product data to derive actionable insights, recommend similar customers, and group customers into meaningful segments.

## Repository Structure

### Data Files
- **Customers.csv**: Contains customer profile information (e.g., CustomerID, Name, Region, SignupDate).
- **Products.csv**: Contains product details (e.g., ProductID, Name, Category, Price).
- **Transactions.csv**: Contains transaction history (e.g., TransactionID, CustomerID, ProductID, Quantity, TotalValue, Price, TransactionDate).

### Notebooks and Reports
- **Anuneet_Rastogi_EDA.ipynb**: Jupyter Notebook for exploratory data analysis (EDA), including data cleaning, visualization, and business insights generation.
- **Anuneet_Rastogi_EDA.pdf**: PDF report summarizing the EDA process and derived business insights.

- **Anuneet_Rastogi_Lookalike.ipynb**: Jupyter Notebook for the lookalike model, which recommends similar customers based on their profiles and transaction histories.
- **Anuneet_Rastogi_Lookalike.csv**: Output of the lookalike model, mapping customer IDs to their top 3 similar customers with similarity scores.

- **Anuneet_Rastogi_Clustering.ipynb**: Jupyter Notebook for customer segmentation using clustering techniques, including clustering metrics like Davies-Bouldin Index and silhouette scores.
- **Anuneet_Rastogi_Clustering.pdf**: PDF report summarizing clustering results, including the number of clusters, metrics, and visualizations.

### Visualizations
- **avgprice.png**: Visualization of average product price by category.
- **cluster.png**: Scatter plot showing customer segmentation clusters.
- **customer_signup.png**: Trend of customer signups over time.
- **regionsale.png**: Total sales distribution by region.
- **top10.png**: Bar chart of the top 10 products by total sales.
- **total_sale.png**: Line chart of total sales over time.

## Key Features
1. **Exploratory Data Analysis (EDA):**
   - Cleaned and visualized customer, product, and transaction data.
   - Generated insights on sales trends, regional distribution, top products, and customer sign-up patterns.

2. **Lookalike Model:**
   - Identifies top 3 similar customers for each customer based on transaction and profile data.
   - Computes similarity scores using cosine similarity.

3. **Customer Segmentation:**
   - Groups customers into clusters using K-Means clustering.
   - Evaluates clustering performance with Davies-Bouldin Index and silhouette scores.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Anuneet2003/EDA-Lookalike-Segmentation.git
   ```
2. Place the required CSV files (`Customers.csv`, `Products.csv`, `Transactions.csv`) in the repository folder.
3. Open the provided notebooks in Jupyter Notebook or Jupyter Lab and run the cells step by step.
4. Review the generated outputs:
   - PDF reports for EDA and clustering results.
   - CSV file for lookalike recommendations.
   - PNG visualizations for various analyses.

## Requirements
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, fpdf
- Jupyter Notebook for running `.ipynb` files

## License
This project is open-source.

## Author
Anuneet Rastogi
