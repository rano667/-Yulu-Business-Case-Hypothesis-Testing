
# 🚲 Yulu Business Case: Hypothesis Testing

This project focuses on analyzing rental patterns of electric bicycles (like Yulu) to evaluate business hypotheses using statistical testing methods. The objective is to determine whether there is a significant difference in the number of electric cycles rented on working days versus non-working days.

---

## 📊 Problem Statement

**Business Question:**  
_Is there a significant difference in Yulu bike rentals between working days and non-working days?_

To answer this, hypothesis testing was conducted on historical rental data using a two-sample t-test approach.

---

## 🔗 Project Links

- 📒 **Google Colab Notebook**: [Open in Colab](https://colab.research.google.com/drive/1cDqdii3A5q6DvA29AoNSL-3XJR2_ltTj?usp=sharing)  
- 📂 **Dataset**: [Download CSV](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089)

---

## 📁 Dataset Features

The dataset includes the following columns:

- `datetime`: Timestamp of rental
- `season`, `holiday`, `workingday`, `weather`: Categorical descriptors
- `temp`, `atemp`, `humidity`, `windspeed`: Environmental conditions
- `casual`, `registered`, `count`: Number of rentals

---

## 📌 Key Steps in the Analysis

- Load and explore the dataset
- Group records by working vs. non-working days
- Check for normality and equal variances
- Perform independent two-sample t-test
- Interpret the p-value and conclude

---

## 📈 Result Summary

- **P-value**: 0.2264
- **Conclusion**: Since the p-value is greater than the alpha level (0.05), we **fail to reject** the null hypothesis.
- **Interpretation**: There is **no statistically significant difference** in electric bike rentals between working days and non-working days.

---

## 🛠️ Tools Used

- Python 3
- Google Colab
- Libraries: `pandas`, `matplotlib`, `seaborn`, `scipy.stats`

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yulu-hypothesis-testing.git
   cd yulu-hypothesis-testing
   ```

2. Open the notebook using [Google Colab](https://colab.research.google.com/):
   - [Click here to open](https://colab.research.google.com/drive/1cDqdii3A5q6DvA29AoNSL-3XJR2_ltTj?usp=sharing)

3. Run all cells to execute the analysis.  
   Make sure to upload or connect to the dataset:
   - [bike_sharing.csv](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089)

---

## 📬 Contact

**Author:** Ranjan Mondal  
📧 Email: [ranjanm667@gmail.com]  
🔗 [www.linkedin.com/in/ranjan-mondal]

---

> ⚠️ _This project is for educational purposes and explores statistical hypothesis testing on publicly available data._
