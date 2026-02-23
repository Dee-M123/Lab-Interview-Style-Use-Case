**Airbnb Berlin Market Analysis**

**Exploratory Data Analysis & Business Insights**

**Project Objective**

- Conduct a full exploratory data analysis (EDA) on Berlin Airbnb listings to:

- Clean messy real-world data

- Identify key market patterns

- Define realistic business questions

- Provide data-backed insights


**Project Structure**

Airbnb-Berlin-EDA/

│

├── data/

│   ├── raw_data.csv  

│

├── notebooks/

│   └── eda_analysis.ipynb

│

└── README.md

data/ → Raw datasets

notebooks/ → Full EDA and analysis workflow

visuals/ → Key plots used for insights

README.md → Project summary



**1. Data Preparation**


**Key preprocessing steps**:


✔ Fixed text encoding issues

✔ Converted price and ratings to numeric

✔ Cleaned percentage and categorical fields

✔ Removed sparse and non-analytical columns

✔ Standardized column naming

Ensured clean, analysis-ready data.



**2. Exploratory Analysis**

A. **Price Distribution**


- Right-skewed distribution

- Majority of listings under €120

- Small luxury tail

Insight: Market dominated by mid-range listings.



**B. Listings by Neighborhood**


- Highest supply in Mitte & Friedrichshain-Kreuzberg

- Lower density in outer districts

Insight: Supply concentrated in central districts.



**C. Correlation Analysis**


Strong price drivers:

- Accommodates

- Bedrooms

- Beds

- Price shows near-zero correlation with overall rating.

Insight: Capacity drives pricing, not satisfaction.



**D. Price vs Rating**


- Ratings clustered between 85–100

- No strong price-rating relationship

Insight: Higher price does not guarantee better reviews.



**3. Business Questions & Answers**


1️⃣ What drives listing price?
Property capacity is the primary determinant.

2️⃣ Does higher price lead to higher satisfaction?
No measurable relationship found.

3️⃣ Which neighborhoods dominate the market?
Central districts lead in supply.

4️⃣ Is the market segmented?
Yes — high-volume mid-range and smaller luxury segment.



**Key Takeaways**


- Size drives price

- Price ≠ satisfaction

- Centralization of supply

- Ratings highly clustered

- Clear market segmentation

  

**Tools Used**


    Python (Pandas, NumPy)
    
    Seaborn & Matplotlib
    
    Statistical & correlation analysis
    

**If needed, this project can be extended into:**


- Pricing optimization analysis

- Neighborhood competitiveness modeling

- Host performance benchmarking
