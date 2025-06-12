# CartIQ – A Customer Segment Analysis

**Description:**

CartIQ is a data analytics project using RFM modeling and clustering to segment customers into VIP, Loyal, At-Risk, and Lost.  
Built with Python, Pandas, and Scikit-learn during an internship at Tavant Technologies, it delivers insights for targeted marketing and customer retention.

---

## Features
- RFM (Recency, Frequency, Monetary) Analysis
- Customer segmentation using K-Means clustering
- Identification of customer categories: VIP, Loyal, At-Risk, Lost
- Insightful visualizations and metrics

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Output
- Customer segments with labels
- Visual charts for better understanding
- Actionable insights for marketing teams

---

## Project Workflow

### Step 1: Load the Data
- Import the customer transaction dataset (CSV or Excel format).
- Explore initial structure and fields (e.g., Customer ID, Invoice Date, Amount).

### Step 2: Clean the Data
- Handle missing values and duplicates.
- Convert date fields to datetime format.
- Remove records with negative or null values (e.g., returns or invalid entries).

### Step 3: Calculate RFM Values
- **Recency:** Days since the last purchase.
- **Frequency:** Total number of purchases.
- **Monetary:** Total amount spent by each customer.

### Step 4: Normalize RFM Scores
- Apply Min-Max scaling or StandardScaler to standardize RFM values.
- This ensures fair distance calculation during clustering.

### Step 5: Apply Clustering Algorithm
- Use K-Means to segment customers based on RFM features.
- Determine optimal number of clusters using Elbow Method or Silhouette Score.

### Step 6: Label and Analyze Segments
- Assign meaningful labels like VIP, Loyal, At-Risk, and Lost.
- Visualize cluster distribution using scatter plots and bar charts.

### Step 7: Interpret and Export Results
- Provide actionable business insights for marketing and retention.
- Save the final segmented dataset for future use or dashboard integration.
