# Financial Sentiment Analysis Questions and Answers

This document contains 16 questions related to financial sentiment analysis, along with their answers and detailed explanations.

---

## Question 1:
**What is the primary limitation of using only domain-specific dictionaries for sentiment analysis?**

### Answer:
**Boxed Answer: \(\boxed{\text{They are created based on specific and relatively small datasets}}\)**

### Explanation:
Domain-specific dictionaries are often built using data from narrow contexts, leading to incomplete coverage of sentiment terms and potential bias. This is a significant limitation when applied to broader or more diverse datasets.

---

## Question 2:
**What is the most robust approach to cryptocurrency sentiment analysis using Reddit data?**

### Answer:
**Boxed Answer: \(\boxed{\text{Combining sentiment scores with market-specific terminology analysis}}\)**

### Explanation:
Combining general sentiment analysis with domain-specific terminology ensures that both emotional tone and cryptocurrency-relevant terms (e.g., "bullish," "FOMO") are considered, providing a comprehensive understanding of sentiment.

---

## Question 3:
**What is the difference between `CountVectorizer` and `TfidfVectorizer`?**

### Answer:
**Boxed Answer: \(\boxed{\text{TfidfVectorizer considers term importance across corpus while CountVectorizer only counts term frequency}}\)**

### Explanation:
`CountVectorizer` simply counts word occurrences, while `TfidfVectorizer` weighs terms by their importance across documents, reducing the impact of common words and highlighting meaningful ones.

---

## Question 4:
**Calculate the TF-IDF score for the term "trading" given the following: Term Frequency = 5/100, IDF = log(10/3).**

### Answer:
**Boxed Answer: \(\boxed{0.0602}\)**

### Explanation:
TF-IDF is calculated as \( \text{TF} \times \text{IDF} \). Here, \( \text{TF} = 0.05 \) and \( \text{IDF} = \ln(10/3) \approx 1.204 \), so \( \text{TF-IDF} = 0.05 \times 1.204 = 0.0602 \).

---

## Question 5:
**What is the Minkowski distance between vectors \( X = [1, 1, 1] \) and \( Y = [2, 2, 2] \) with \( p = 3 \)?**

### Answer:
**Boxed Answer: \(\boxed{1.44}\)**

### Explanation:
The Minkowski distance formula is \( d(X, Y) = \left( \sum_{i=1}^n |x_i - y_i|^p \right)^{1/p} \). Substituting values, \( d(X, Y) = \left( 3 \right)^{1/3} \approx 1.44 \).

---

## Question 6:
**What is the primary limitation of StockTwits sentiment analysis?**

### Answer:
**Boxed Answer: \(\boxed{\text{Sentiment tags reflect subjective opinions that may include personal biases}}\)**

### Explanation:
StockTwits sentiment tags are user-generated and thus prone to individual biases, which may not accurately represent objective market sentiment.

---

## Question 7:
**Which similarity measure is most appropriate for comparing company descriptions in regulatory filings?**

### Answer:
**Boxed Answer: \(\boxed{\text{Cosine Similarity with TF-IDF}}\)**

### Explanation:
Cosine similarity with TF-IDF is ideal for high-dimensional text data like regulatory filings, as it captures semantic similarity and accounts for term importance.

---

## Question 8:
**What distinguishes the Cambridge Dictionary's definition of social media?**

### Answer:
**Boxed Answer: \(\boxed{\text{Its emphasis on technological platforms over social aspects}}\)**

### Explanation:
The Cambridge Dictionary focuses on the technological infrastructure of social media rather than its social interaction aspects.

---

## Question 9:
**What is the best way to design a system to monitor emerging market risks using Google Trends data?**

### Answer:
**Boxed Answer: \(\boxed{\text{Integrate rising queries with risk-related terms and validate with market indicators}}\)**

### Explanation:
By combining rising queries with domain-specific risk terms and validating against market indicators, one can effectively identify emerging risks.

---

## Question 10:
**What is the cosine similarity between vectors \( A = (0.5, 0.3) \) and \( B = (0.4, 0.2) \)?**

### Answer:
**Boxed Answer: \(\boxed{0.997}\)**

### Explanation:
Cosine similarity is calculated as \( \frac{\mathbf{A} \cdot \mathbf{B}}{\|\mathbf{A}\| \|\mathbf{B}\|} \). Substituting values gives \( \approx 0.997 \).

---

## Question 11:
**Why is domain-specific sentiment analysis for financial tweets challenging?**

### Answer:
**Boxed Answer: \(\boxed{\text{Financial tweets contain technical jargon and polysemic terms with context-dependent meanings}}\)**

### Explanation:
Financial tweets use specialized language and terms with multiple meanings, making sentiment analysis more complex.

---

## Question 12:
**How does Named Entity Recognition (NER) enhance TF-IDF analysis in financial contexts?**

### Answer:
**Boxed Answer: \(\boxed{\text{It identifies specific companies and relationships}}\)**

### Explanation:
NER extracts entities like company names and relationships, enriching TF-IDF analysis by focusing on key financial terms.

---

## Question 13:
**What characteristic of social media data provides the most comprehensive insight into market sentiment?**

### Answer:
**Boxed Answer: \(\boxed{\text{The multi-dimensional nature of user interactions that combine explicit opinions with implicit behavioral patterns}}\)**

### Explanation:
Social media data captures both explicit opinions (e.g., text) and implicit behaviors (e.g., likes, shares), offering a holistic view of sentiment.

---

## Question 14:
**What is the most effective approach for developing a new trading strategy using Google Trends data?**

### Answer:
**Boxed Answer: \(\boxed{\text{Integrate rising queries analysis with traditional technical indicators}}\)**

### Explanation:
Combining search trends with technical indicators leverages both behavioral insights and quantitative market data for better decision-making.

---

## Question 15:
**(Placeholder for uploaded image question)**

---

## Question 16:
**(Placeholder for uploaded image question)**

---