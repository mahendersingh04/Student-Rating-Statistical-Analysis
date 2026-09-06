# 📊 Student Rating Statistical Analysis

> Statistical analysis and visualization of student rating data using Python.

---

## 🎯 Objective

To analyze student rating data using Python and apply statistical
methods to understand tenure, age, gender, minority status, and
teaching evaluation scores.

---

## 📚 Practical Overview

This practical focuses on statistical analysis and data visualization
using the TeachingRatings dataset.

The analysis includes:

- Minority and tenure analysis
- Age comparison by tenure status
- Age distribution visualization
- Gender distribution visualization
- Teaching evaluation analysis
- Group-wise statistical analysis

---

## 📊 Dataset

The analysis uses the **TeachingRatings** dataset.

The dataset contains information about professors and their teaching
evaluations, including variables related to:

- Minority status
- Tenure status
- Age
- Gender
- Teaching evaluation score

---

## 🔍 Analysis Performed

### 1. Minority Status and Tenure

The percentage of visible minority professors who are tenured is
calculated and compared with non-minority professors.

| Group | Tenured Percentage |
|---|---:|
| Visible Minority | 76.47% |
| Non-Minority | 78.29% |

The difference is approximately **1.8 percentage points**.

The analysis indicates that tenure status does not significantly differ
based on minority status in the provided analysis.

---

### 2. Age Comparison by Tenure

Mean age and standard deviation are calculated separately for tenured
and untenured professors.

| Tenure Status | Mean Age | Standard Deviation |
|---|---:|---:|
| Untenured | 41.28 years | 7.68 years |
| Tenured | 50.15 years | 9.41 years |

Tenured professors are approximately **8.87 years older on average**
than untenured professors.

---

### 3. Age Distribution

A **histogram with Kernel Density Estimation (KDE)** is used to
visualize the age variable.

A histogram is appropriate because age is a continuous numerical
variable and the graph helps visualize its:

- Distribution
- Central tendency
- Spread
- Skewness

---

### 4. Gender Distribution

A bar chart is used to visualize the number of professors by gender.

The practical also compares:

| Function | Chart Orientation |
|---|---|
| `pyplot.bar()` | Vertical |
| `pyplot.barh()` | Horizontal |

`pyplot.bar()` places categories on the x-axis and values on the
y-axis, while `pyplot.barh()` places categories on the y-axis and
values on the x-axis.

---

### 5. Median Evaluation Score

The median teaching evaluation score is calculated for tenured
professors.

**Median Evaluation Score: 4.0**

---

## 📈 Visualizations

The practical includes:

- Age Distribution Histogram
- Age Distribution with KDE
- Professor Count by Gender

These visualizations help understand the distribution and categorical
composition of the dataset.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Statsmodels | Dataset loading |
| Jupyter Notebook | Development environment |

---

## 💻 Implementation

### Import Libraries

```python
import statsmodels.api as sm
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
