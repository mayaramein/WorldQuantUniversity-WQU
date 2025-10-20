# Investment Risk & Financial Mathematics Q&A

## Question 1
**Given a symmetric matrix, is it positive definite?**

### Answer:
✅ **"Yes, because its determinant is positive (16) and all eigenvalues are positive."**

### Explanation:
A symmetric matrix is **positive definite** if all its eigenvalues are **positive**. A positive determinant alone is not enough, but if all eigenvalues are positive, the matrix is confirmed to be positive definite.

---

## Question 2
**How does semivariance improve upon variance when measuring risk?**

### Answer:
✅ **"By focusing only on downside deviations, providing a measure of downside risk."**

### Explanation:
- **Variance** considers both upside and downside deviations.
- **Semivariance** only focuses on **downside risk**, making it more relevant for risk-averse investors.

---

## Question 3
**For a symmetric nxn matrix A and a non-zero vector x, which Rayleigh quotient statement is true?**

### Answer:
✅ **"If A is positive definite, then R(A, x) > 0 for all non-zero x."**

### Explanation:
The **Rayleigh quotient** measures how a vector interacts with a matrix. If **A is positive definite**, all its eigenvalues are positive, ensuring \( R(A, x) > 0 \) for all non-zero vectors x.

---

## Question 4
**Calculate the Sharpe Ratio given a portfolio return of 12%, a risk-free rate of 2%, and a standard deviation of 20%.**

### Answer:
✅ **0.5**

### Explanation:
\[ Sharpe Ratio = \frac{(Portfolio Return - Risk-Free Rate)}{Standard Deviation} \]
\[ = \frac{(12\% - 2\%)}{20\%} = \frac{10\%}{20\%} = 0.5 \]

---

## Question 5
**Given daily log returns with a mean of 0.001 and standard deviation of 0.02, what is the probability of a daily return exceeding 0.04?**

### Answer:
✅ **2.56%**

### Explanation:
Using the Z-score formula:
\[ Z = \frac{(X - \mu)}{\sigma} = \frac{0.04 - 0.001}{0.02} = 1.95 \]
Looking up **P(Z > 1.95)** in the normal distribution table gives **2.56%**.

---

## Question 6
**What are the three distinct approaches to measuring investment volatility?**

### Answer:
✅ **"High-low metric, moving average rolling distance, and standard deviation of returns."**

### Explanation:
These methods capture **historical fluctuations** and provide insight into risk.

---

## Question 7
**How can Benford's Law detect accounting manipulation?**

### Answer:
✅ **"By analyzing the frequency distribution of first digits in financial data."**

### Explanation:
Benford’s Law states that **leading digits in real-world numerical datasets follow a predictable pattern**. Deviations can indicate fraud.

---

## Question 8
**What is \( L_{22} \) in the Cholesky factorization of the given symmetric matrix?**

### Answer:
✅ **\( \sqrt{4} = 2 \)**

### Explanation:
Cholesky factorization decomposes a matrix into a lower triangular matrix. The diagonal elements are square roots of leading submatrix determinants.

---

## Question 9
**If an asset's returns exhibit high positive skewness, what can be inferred?**

### Answer:
✅ **"The distribution has a longer right tail indicating potential for extreme positive returns."**

### Explanation:
- **Positive skew** → long **right** tail.
- **Negative skew** → long **left** tail.

---

## Question 10
**What is the determinant of an upper triangular matrix?**

### Answer:
✅ **"The product of its diagonal elements."**

### Explanation:
For an **upper triangular matrix**, the determinant is simply the product of diagonal elements.

---

## Question 11
**What is the approximate 3-sigma upper bound for daily log returns with mean 0.0005 and standard deviation 0.02?**

### Answer:
✅ **0.0605**

### Explanation:
\[ \mu + 3\sigma = 0.0005 + (3 \times 0.02) = 0.0605 \]

---

## Question 12
**What is the future value of a $5,000 investment after 3 years with an annual interest rate of 8%?**

### Answer:
✅ **$6,298.56**

### Explanation:
Using compound interest formula:
\[ FV = PV (1 + r)^t \]
\[ = 5000 (1.08)^3 = 6298.56 \]

---

## Question 13
**Why do indices typically show lower volatility than individual stocks?**

### Answer:
✅ **"Diversification across multiple stocks reduces overall portfolio volatility."**

### Explanation:
Diversification helps smooth out extreme fluctuations.

---

## Question 14
**What was Ernst & Young's ethical violation that led to regulatory action?**

### Answer:
✅ **"Cheating on their ethics exam."**

### Explanation:
E&Y employees were caught cheating on CPA ethics exams, leading to legal and reputational consequences.

---

## Question 15
**Which of the following matrices is symmetric positive definite?**

### Answer:
✅ **The one with all positive eigenvalues.**

### Explanation:
A matrix is positive definite if **all eigenvalues are positive**.

---

## Question 16
**In the Jarque-Bera test for normality, what does a p-value of 0.0 indicate?**

### Answer:
✅ **"Strong evidence against normal distribution."**

### Explanation:
A p-value close to 0 means the dataset **strongly deviates** from normality.

