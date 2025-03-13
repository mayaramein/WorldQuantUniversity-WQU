# FM Graded Quiz M7

## Question 1
**Which factor most significantly impacts the quality of climate projections?**  
✅ **Answer:** The accuracy and completeness of input data used in climate models.  

### Explanation:
Climate models rely heavily on **accurate and comprehensive input data**. Without precise data, even the best computational models cannot generate reliable climate projections.

---

## Question 2
**For a dataset with mean = 15, standard deviation = 3, and x = 21, what is the z-score?**  
✅ **Answer:** 2  

### Explanation:
The z-score formula is:
\[
z = \frac{x - \mu}{\sigma}
\]
Substituting values:
\[
z = \frac{21 - 15}{3} = 2
\]

---

## Question 3
**In a machine learning context, what is the primary purpose of elastic nets?**  
✅ **Answer:** To combine both LASSO and Ridge regression methods.  

### Explanation:
Elastic Net **balances** LASSO (L1 regularization) and Ridge (L2 regularization), making it useful for **handling multicollinearity** and **selecting important features**.

---

## Question 4
**What is the primary purpose of using the LASSO method in variable selection?**  
✅ **Answer:** To automatically perform feature selection by shrinking coefficients to zero.  

### Explanation:
LASSO (Least Absolute Shrinkage and Selection Operator) uses **L1 regularization**, forcing some coefficients to **exactly zero**, effectively selecting important features.

---

## Question 5
**What factors should be considered when choosing between different normalization methods?**  
✅ **Answer:** Data distribution, presence of outliers, and intended analysis method.  

### Explanation:
Normalization should consider:
- **Data distribution** (e.g., Min-Max scaling for uniform data, Z-score for normal).
- **Presence of outliers** (Robust scaling is better).
- **Intended analysis method** (Distance-based models often require scaling).

---

## Question 6
**What transformation would you apply to create a volume-weighted average price (VWAP)?**  
✅ **Answer:** Sum of (Price × Volume) divided by Total Volume.  

### Explanation:
VWAP formula:
\[
VWAP = \frac{\sum (Price \times Volume)}{\sum Volume}
\]
It represents the **average trading price weighted by volume**.

---

## Question 7
**Why is NetCDF4 considered a self-describing data format?**  
✅ **Answer:** It contains both the data and its metadata including attributes information.  

### Explanation:
NetCDF4 files store **both data and metadata**, making them **self-describing**. Metadata includes **variable names, dimensions, and attributes**.

---

## Question 8
**For a 30-day rolling window, if the mean is 20 and std is 5, what is the normalized value for x = 25?**  
✅ **Answer:** 1  

### Explanation:
Using the z-score formula:
\[
z = \frac{x - \mu}{\sigma} = \frac{25 - 20}{5} = 1
\]

---

## Question 9
**What is the key characteristic of Principal Component Analysis in data reduction?**  
✅ **Answer:** It creates orthogonal components ranked by decreasing variance.  

### Explanation:
PCA transforms data into **uncorrelated (orthogonal) components** ranked by **variance**, helping in **dimensionality reduction**.

---

## Question 10
**Which advanced method of data imputation involves modeling the conditional expectation of missing values given observed data?**  
✅ **Answer:** Expectation Maximization Algorithm.  

### Explanation:
The **Expectation-Maximization (EM)** algorithm iteratively estimates missing values by maximizing the likelihood of observed data.

---

## Question 11
**How can you determine if a dataset requires robust scaling?**  
✅ **Answer:** Analyze the presence and impact of outliers.  

### Explanation:
**Robust scaling** uses the **median and IQR**, making it more **resistant to outliers** than Min-Max or standard scaling.

---

## Question 12
**How would you calculate the adjusted closing price given a 2-for-1 stock split and a $1 dividend?**  
✅ **Answer:** Divide the closing price by 2 and subtract the dividend.  

### Explanation:
- **Stock split (2-for-1)** → Divide price by **2**.
- **Dividend adjustment** → Subtract **$1**.

---

## Question 13
**How does reanalysis improve the quality of climate data?**  
✅ **Answer:** It combines historical observations with forecasted data to fill gaps and provide consistent global coverage.  

### Explanation:
Reanalysis **blends observations with models** to **fill missing data** and improve **global consistency**.

---

## Question 14
**If a matrix has IQR = 4 and median = 10, what is the robust scaled value for x = 18?**  
✅ **Answer:** 2  

### Explanation:
Robust scaling formula:
\[
X_{\text{scaled}} = \frac{X - \text{Median}}{\text{IQR}}
\]
\[
= \frac{18 - 10}{4} = 2
\]

---

## Question 15
**What approach would you take to implement a robust debugging system for a financial model?**  
✅ **Answer:** Implement systematic checks for financial constraints and mathematical consistency.  

### Explanation:
- **Check financial constraints** (e.g., balance sheet consistency).
- **Ensure mathematical correctness**.
- **Run unit tests and sensitivity analysis**.

---

## Question 16
**In the context of outlier detection in financial time series, what is the most robust approach for identifying extreme values?**  
✅ **Answer:** Combine statistical measures, domain expertise, and diagnostic plots.  

### Explanation:
A robust method should:
- **Use statistical tests** (Z-score, MAD, IQR).
- **Leverage domain knowledge** (e.g., market events).
- **Visualize outliers** using diagnostic plots.

