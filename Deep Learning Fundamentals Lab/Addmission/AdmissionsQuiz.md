# Deep Learning Fundamentals Lab — Admissions Quiz Review

This document contains all 24 practice questions from the Admissions Quiz for the **Deep Learning Fundamentals Lab**, along with correct answers and detailed explanations.  
It covers four core topics: **Linear Algebra**, **Calculus**, **Probability & Statistics**, and **Python Programming**.

---

## 🔢 Linear Algebra

### **Question 1**  
**What does the transpose of a matrix do?**  

✅ **Answer**: Swaps rows and columns  

**Explanation**:  
The transpose of a matrix flips it over its diagonal: rows become columns and columns become rows. For example:

Original: Transpose:
[1 2] [1 3 5]
[3 4] → [2 4 6]
[5 6]

Other options (sorting, negating, inverting) describe unrelated operations.

---

### **Question 2**  
**Why can’t you multiply a 2×3 matrix by a 2×4 matrix?**  

✅ **Answer**: Inner dimensions don't match (3 ≠ 2)  

**Explanation**:  
Matrix multiplication A × B requires that the number of **columns in A** equals the number of **rows in B**. Here, A is 2×3 (3 columns), B is 2×4 (2 rows). Since 3 ≠ 2, multiplication is undefined.

---

### **Question 3**  
**What is the trace of the following matrix?**  
[3 1 2]
[0 5 1]
[2 3 4]


✅ **Answer**: 12  

**Explanation**:  
The trace is the sum of diagonal elements: 3 (row 1, col 1) + 5 (row 2, col 2) + 4 (row 3, col 3) = **12**.

---

### **Question 4**  
**Which operation is always valid for two matrices of the same size?**  

✅ **Answer**: Addition  

**Explanation**:  
Matrix addition is defined element-wise and only requires matching dimensions. Multiplication requires compatible inner dimensions; division and determinant operations are not generally defined for arbitrary same-sized matrices.

---

### **Question 5**  
**When does a system of linear equations have infinitely many solutions?**  

✅ **Answer**: When equations are dependent with free variables  

**Explanation**:  
If one or more equations are linear combinations of others, the system is **dependent**, leading to **free variables** and infinitely many solutions (e.g., `x + y = 2` and `2x + 2y = 4`).

---

### **Question 6**  
**True or False: Every matrix has eigenvalues.**  

✅ **Answer**: False. Some matrices have no eigenvalues  

**Explanation**:  
Eigenvalues are only defined for **square matrices**. Rectangular matrices have **no eigenvalues**. Even among square matrices, real eigenvalues may not exist without allowing complex numbers—but the statement says “every matrix,” which includes non-square ones.

---

## 📐 Calculus

### **Question 7**  
**What is the chain rule used for?**  

✅ **Answer**: Finding derivatives of composite functions  

**Explanation**:  
The chain rule computes the derivative of `f(g(x))` as `f’(g(x)) ⋅ g’(x)`. It’s essential for backpropagation in neural networks.

---

### **Question 8**  
**Why is f(x) = |x| not differentiable at x = 0?**  

✅ **Answer**: Left and right derivatives are different  

**Explanation**:  
- Right derivative at 0: slope of `y = x` → **+1**  
- Left derivative at 0: slope of `y = -x` → **–1**  
Since they differ, the derivative doesn’t exist at x = 0—even though the function is continuous.

---

### **Question 9**  
**What is the derivative of f(x) = e^{3x}?**  

✅ **Answer**: `3e^{3x}`  

**Explanation**:  
Using the chain rule: derivative of `e^{u}` is `e^{u} ⋅ u’`. Here, `u = 3x`, so `u’ = 3`. Thus, `d/dx[e^{3x}] = 3e^{3x}`.

---

### **Question 10**  
**What is the gradient of f(x, y) = x² + 2xy + y² at (1, 1)?**  

✅ **Answer**: (4, 4)  

**Explanation**:  
- ∂f/∂x = 2x + 2y → at (1,1): 2+2 = 4  
- ∂f/∂y = 2x + 2y → at (1,1): 2+2 = 4  
So ∇f(1,1) = (4, 4).

---

### **Question 11**  
**How do you determine concavity of a function?**  

✅ **Answer**: Check the sign of the second derivative  

**Explanation**:  
- f''(x) > 0 → concave up  
- f''(x) < 0 → concave down  
This is a standard method in calculus for analyzing curvature.

---

### **Question 12**  
**True or False: Every continuous function has an antiderivative.**  

✅ **Answer**: True by Fundamental Theorem of Calculus  

**Explanation**:  
The Fundamental Theorem of Calculus guarantees that if `f` is continuous on `[a,b]`, then `F(x) = ∫ₐˣ f(t) dt` is an antiderivative of `f`. So yes—every continuous function has at least one antiderivative.

---

## 📊 Probability & Statistics

### **Question 13**  
**What is the difference between a population and a sample?**  

✅ **Answer**: Population is all data, sample is a subset  

**Explanation**:  
- **Population**: Entire group of interest  
- **Sample**: Subset used to estimate population characteristics  
This distinction is foundational in inferential statistics.

---

### **Question 14**  
**What distinguishes discrete and continuous distributions?**  

✅ **Answer**: Discrete has countable outcomes, continuous has intervals  

**Explanation**:  
- Discrete: e.g., number of heads (0, 1, 2…) — countable  
- Continuous: e.g., height, time — any value in an interval (uncountable)

---

### **Question 15**  
**Which distribution models coin flips?**  

✅ **Answer**: Binomial  

**Explanation**:  
Coin flips are Bernoulli trials. The number of heads in `n` flips follows a **Binomial(n, p)** distribution.

---

### **Question 16**  
**What is the probability of exactly 2 heads in 3 fair coin flips?**  

✅ **Answer**: 3/8  

**Explanation**:  
There are 8 total outcomes. Favorable: HHT, HTH, THH → 3 outcomes. So P = 3/8.  
Alternatively: C(3,2) × (0.5)² × (0.5) = 3 × 0.125 = 0.375 = 3/8.

---

### **Question 17**  
**Why doesn’t correlation imply causation?**  

✅ **Answer**: Confounding variables may exist  

**Explanation**:  
A third variable (confounder) might influence both observed variables, creating a spurious correlation (e.g., ice cream sales and drowning both increase in summer).

---

### **Question 18**  
**Does a larger sample always give a better estimate?**  

✅ **Answer**: True if sampling is unbiased  

**Explanation**:  
Larger samples reduce variance—but only if the sampling method is **unbiased**. Biased sampling (e.g., convenience sample) leads to precise but inaccurate estimates.

---

## 🐍 Python Programming

### **Question 19**  
**Which keyword defines a class in Python?**  

✅ **Answer**: `class`  

**Explanation**:  
Syntax: `class MyClass:`. Other options (`type`, `object`, `struct`) are not used to define classes in standard Python.

---

### **Question 20**  
**How do you create an empty dictionary in Python?**  

✅ **Answer**: `{}` or `dict()`  

**Explanation**:  
Both `{}` and `dict()` create empty dictionaries.  
- `[]` → list  
- `()` → tuple  
- `{None}` → set (not a dict!)

---

### **Question 21**  
**What is the scope of a variable defined inside a function?**  

✅ **Answer**: Local to that function  

**Explanation**:  
Local variables exist only during the function call and cannot be accessed outside the function.

---

### **Question 22**  
**What’s the difference between `==` and `is` in Python?**  

✅ **Answer**: `==` checks if values are equal, `is` checks if they're the same object  

**Explanation**:  
- `==` → compares content  
- `is` → compares identity (memory address)  
Example: two lists with same values are `==` but not `is`.

---

### **Question 23**  
**When should you use a `while` loop instead of a `for` loop?**  

✅ **Answer**: When iteration count is unknown  

**Explanation**:  
Use `while` when looping until a condition is met (e.g., user input, convergence). Use `for` when the number of iterations is known (e.g., over a list or range).

---

### **Question 24**  
**How do you make a read-only property in Python?**  

✅ **Answer**: Use underscore prefix and `@property` decorator  

**Explanation**:  
Example:
```python
class MyClass:
    def __init__(self, value):
        self._value = value
    @property
    def value(self):
        return self._value
