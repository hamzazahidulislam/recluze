<!-- @format -->

# Codanics

# Levels of Measurement: A Statistical Hierarchy

This document outlines the four levels of measurement used in statistics to help determine which mathematical operations and statistical tests are appropriate for a given dataset.

---

## Table of Contents

1. [Nominal Level](#1-nominal-level-labels)
2. [Ordinal Level](#2-ordinal-level-order)
3. [Interval Level](#3-interval-level-fixed-spacing)
4. [Ratio Level](#4-ratio-level-the-gold-standard)
5. [Summary Comparison](#summary-comparison-table)

---

## 1. Nominal Level (Labels)

> **Definition:** Used for **categorizing** or labeling variables without any quantitative value or internal order. You can only calculate the _mode_ and _frequencies_.

- **Eye Color:** Brown, Blue, Green, Hazel.
- **Blood Type:** A, B, AB, O.
- **Marital Status:** Single, Married, Divorced, Widowed.
- **Binary Outcomes:** Yes/No, Pass/Fail.

---

## 2. Ordinal Level (Order)

> **Definition:** Data has a **specific order or rank**, but the "distance" between the ranks is unknown or inconsistent.

- **Satisfaction Surveys:** Very Unsatisfied, Neutral, Very Satisfied.
- **Socioeconomic Status:** Low income, Middle income, High income.
- **Race Results:** Gold, Silver, and Bronze medals. (The time gap between medals varies).
- **Education Level:** High School, Bachelor’s, Master’s, PhD.

---

## 3. Interval Level (Fixed Spacing)

> **Definition:** Data has a **meaningful order** and the **intervals between values are equal**. However, it lacks a "true zero"—zero is just a placeholder.

- **Temperature (Celsius/Fahrenheit):** 20°C to 30°C is the same gap as 30°C to 40°C. 0°C doesn't mean "no heat."
- **IQ Scores:** The difference between 100 and 110 is the same as 110 and 120.
- **Dates:** The year 0 is a point in time, not the "absence of time."

---

## 4. Ratio Level (The "Gold Standard")

> **Definition:** Includes all properties of the previous levels plus a **true zero point**. This allows for statements like "twice as much" or "half as many."

- **Physical Dimensions:** Height, Weight, and Length. (0 kg = no weight).
- **Income:** $0 means no money earned.
- **Time:** Measured in seconds, minutes, or hours from a starting point.
- **Age:** Measured in years from the point of birth (0).

---

## Summary Comparison Table

| Level        | Categorizes? | Orders? | Equal Intervals? | True Zero? |
| :----------- | :----------: | :-----: | :--------------: | :--------: |
| **Nominal**  |      ✅      |   ❌    |        ❌        |     ❌     |
| **Ordinal**  |      ✅      |   ✅    |        ❌        |     ❌     |
| **Interval** |      ✅      |   ✅    |        ✅        |     ❌     |
| **Ratio**    |      ✅      |   ✅    |        ✅        |     ✅     |

# Statistical Concepts: Triangulation

This document provides an overview of **Triangulation** in research and statistics, covering its types, advantages, and limitations.

---

## What is Triangulation?

**Triangulation** is the practice of using multiple methods, data sources, investigators, or theories to study a single phenomenon. By approaching a research question from different angles, researchers can cross-verify results and increase the reliability of their findings.

### Types of Triangulation

1. **Methodological:** Combining different methods (e.g., surveys + focus groups).
2. **Data:** Collecting data from different times, spaces, or persons.
3. **Investigator:** Using multiple researchers to observe and analyze the same data.
4. **Theoretical:** Using different theoretical perspectives to interpret a single set of data.

---

## Pros and Cons Analysis

### Advantages (Pros)

| Feature               | Benefit                                                                                            |
| :-------------------- | :------------------------------------------------------------------------------------------------- |
| **Enhanced Validity** | Corroborating evidence from different sources makes the findings more credible.                    |
| **Rich Nuance**       | Provides a more complete picture (e.g., Quantitative shows _trends_, Qualitative shows _reasons_). |
| **Reduced Bias**      | Offsets the inherent weaknesses or biases of a single method or researcher.                        |
| **Discovery**         | Contradictions between data sources can lead to new, unexpected insights.                          |

### Disadvantages (Cons)

| Feature            | Drawback                                                                                 |
| :----------------- | :--------------------------------------------------------------------------------------- |
| **High Cost**      | Requires more funding, tools, and participants than single-method studies.               |
| **Time-Consuming** | Data collection and analysis phases take significantly longer.                           |
| **Complexity**     | Integrating divergent data types (like numbers vs. text) can be technically difficult.   |
| **Conflict**       | Results may contradict each other, making it hard to form a single, cohesive conclusion. |

---

## Summary Checklist for Research

- [ ] Is the research question complex enough to require multiple methods?
- [ ] Do I have the resources (time/budget) for triangulation?
- [ ] Have I defined how I will reconcile conflicting data points?
- [ ] Are the chosen methods independent enough to provide a fresh perspective?

---

_Created for the Research Methods documentation project._

---

# Surrogate Endpoints in Statistics

A **Surrogate Endpoint** is an outcome measure that is used as a proxy for a clinically meaningful endpoint.

## Definition

- **Clinical Endpoint:** Reflects a patient's feelings, functions, or survival (e.g., "Did the patient live?").
- **Surrogate Endpoint:** A biomarker intended to substitute for a clinical endpoint (e.g., "Did their blood sugar drop?").

---

## Comparison Table

| Feature       | Clinical Endpoint          | Surrogate Endpoint           |
| :------------ | :------------------------- | :--------------------------- |
| **Goal**      | Direct measure of benefit  | Indirect measure of benefit  |
| **Timeframe** | Long-term                  | Short-term                   |
| **Ease**      | Difficult/Expensive        | Easy/Cheaper                 |
| **Accuracy**  | High (The "Gold Standard") | Variable (Must be validated) |

---

## Common Examples

1. **Cardiovascular:** Using _Blood Pressure_ as a surrogate for _Stroke/Heart Attack_.
2. **Oncology:** Using _Progression-Free Survival (PFS)_ as a surrogate for _Overall Survival (OS)_.
3. **Diabetes:** Using _HbA1c levels_ as a surrogate for _Microvascular complications_.

---

## Key Risks

> **Warning:** A surrogate endpoint is only useful if it is **validated**. If a drug improves the surrogate but doesn't improve the patient's life or lifespan, the trial is considered a failure in a clinical sense.

---

# Bias in Data: Statistical Overview

**Bias** is a systematic distortion in data that leads to inaccurate conclusions. In statistics, it is the difference between the "Expected Value" of an estimator and the "True Value" of the parameter being studied.

---

## Common Types of Bias

### 1. Selection Bias

- **Definition:** The sample is not representative of the population.
- **Example:** Sampling only daytime shoppers to represent all consumers.

### 2. Recall Bias

- **Definition:** Participants do not remember past events accurately.
- **Example:** Asking people what they ate exactly three weeks ago.

### 3. Non-Response Bias

- **Definition:** When people who choose _not_ to respond have different characteristics than those who do.
- **Example:** An employee satisfaction survey where unhappy employees are too afraid to participate.

### 4. Exclusion Bias

- **Definition:** Systematically excluding certain groups from the dataset.
- **Example:** A clinical trial that excludes elderly patients but applies the drug to all ages.

---

## How to Mitigate Bias

- [ ] **Random Sampling:** Ensure every member of a population has an equal chance of being selected.
- [ ] **Blind Studies:** Prevent researchers or participants from knowing which group is the control.
- [ ] **Data Auditing:** Regularly check datasets for under-represented groups.
- [ ] **Clear Definitions:** Use objective, standardized measurements to reduce human error.

---

> "The first principle is that you must not fool yourself—and you are the easiest person to fool." — Richard Feynman

[https://codanics.com/measurement-bias/](https://codanics.com/measurement-bias/)

---

# Measurement Bias (Systematic Error)

Measurement bias is a systematic flaw in the data collection process that consistently distorts the measurement of a variable.

## Key Types

1. **Instrumental:** Faulty equipment (e.g., uncalibrated sensors).
2. **Respondent:** Participants lying to look better (Social Desirability).
3. **Observer:** The researcher sees what they want to see.
4. **Proxy:** Using a poor surrogate (e.g., using "hours spent in gym" as a proxy for "actual calories burned").

---

## The "Bullseye" Visualization

- **Low Bias + Low Random Error:** Hits the center of the target every time.
- **High Bias + Low Random Error:** Hits a tight cluster, but far away from the center (Reliably Wrong).
- **Low Bias + High Random Error:** Scattered all over the target, but the average is the center.

---

## Prevention Strategies

- [ ] **Calibration:** Regularly test equipment against a known standard.
- [ ] **Blinding:** Use double-blind studies so researchers don't know which group is which.
- [ ] **Anonymity:** Ensure surveys are anonymous to reduce social desirability bias.
- [ ] **Standard Operating Procedures (SOPs):** Use strict scripts and protocols for all data collectors.

---

## [https://codanics.com/data-analysis-and-types-of-data-analysis/](https://codanics.com/data-analysis-and-types-of-data-analysis/)

# Data Analysis and Its Four Types

Data Analysis is the systematic application of statistical and logical techniques to describe, illustrate, and evaluate data.

## The Maturity Model

### 📊 1. Descriptive Analysis

> **Goal:** Summarize what occurred.

- **Metric:** "How many units did we sell?"
- **Key Tools:** Dashboards, Pie Charts, Tables.

### 🔍 2. Diagnostic Analysis

> **Goal:** Understand the "why."

- **Metric:** "Why did our website traffic drop last Tuesday?"
- **Key Tools:** Correlation, Probability, Regression.

### 🔮 3. Predictive Analysis

> **Goal:** Forecast future trends.

- **Metric:** "Which customers are likely to cancel their subscription next month?"
- **Key Tools:** Machine Learning, Trend Lines.

### 💡 4. Prescriptive Analysis

> **Goal:** Determine the best path forward.

- **Metric:** "What is the optimal delivery route to save fuel?"
- **Key Tools:** Optimization Algorithms, AI Simulations.

---

## Analysis Workflow

1. **Data Requirements:** Define what you are measuring.
2. **Data Collection:** Gathering info from various sources.
3. **Data Cleaning:** Removing "garbage" data (outliers/errors).
4. **Data Analysis:** Applying the types listed above.
5. **Visualization:** Turning numbers into charts for stakeholders.

---

[https://codanics.com/population-vs-sample/](https://codanics.com/population-vs-sample/)

---

[https://codanics.com/variability-in-statistics/](https://codanics.com/variability-in-statistics/)

---

# Variability in Statistics

**Variability** refers to how "spread out" or "clustered" the data points are in a distribution.

## Key Measures of Spread

| Measure            | Definition                               | Best Used When...                               |
| :----------------- | :--------------------------------------- | :---------------------------------------------- |
| **Range**          | Difference between max and min.          | You need a quick, rough estimate.               |
| **IQR**            | Range of the middle 50% of data.         | You have outliers or skewed data.               |
| **Variance**       | Average squared deviation from the mean. | Performing advanced statistical calculations.   |
| **Std. Deviation** | Square root of variance.                 | You need to interpret spread in original units. |

---

## Visualizing Variability

### High Variability

- Data is spread out.
- The "bell curve" is short and wide.
- Predictions are less reliable.

### Low Variability

- Data is tightly clustered around the mean.
- The "bell curve" is tall and narrow.
- Predictions are more reliable.

---

## Quick Checklist

- [ ] Calculate the **Range** for a quick look.
- [ ] Use **Standard Deviation** for normal distributions.
- [ ] Use **IQR** if the data has extreme outliers.
- [ ] Compare the **Coefficient of Variation** if comparing two datasets with different units.

---

[https://codanics.com/variance-in-statistics/](https://codanics.com/variance-in-statistics/)

---

[https://codanics.com/standard-deviation/](https://codanics.com/standard-deviation/)

---

# SD vs. Standard Error of the Mean (SEM)

While both measure variability, they serve two distinct purposes in statistical reporting.

## Summary Comparison

> **Standard Deviation (SD)**
>
> - Measures the spread of **individual observations**.
> - Does not change significantly with sample size.
> - Purpose: **Descriptive** (How diverse is the sample?).

> **Standard Error (SEM)**
>
> - Measures the accuracy of the **sample mean**.
> - Decreases as sample size increases.
> - Purpose: **Inferential** (How close is the sample mean to the population mean?).

---

## When to Use Each in a Report

### Use Standard Deviation (SD) when:

- You are describing the characteristics of your participants (e.g., "The average age was 35 ± 5 years").
- You want to show the biological or physical range of a variable.

### Use Standard Error (SEM) when:

- You are presenting a graph to show the effect of a treatment.
- You want to show the precision of your estimate.
- You are calculating **Confidence Intervals**.

---

## The "True Zero" of Uncertainty

If your SEM is very large, it means your sample size is likely too small, and your "average" might change drastically if you tested a different group of people.

---

# Error Bars and Whisker Plots

Visual tools used to communicate the reliability and distribution of statistical data.

## 📊 Error Bars

Error bars are used on charts to indicate the error or uncertainty in a reported measurement.

### Common Settings

- **SD Error Bars:** "How much does the data vary?" (Descriptive).
- **SEM Error Bars:** "How sure am I of this average?" (Inferential).
- **95% CI Error Bars:** "If I repeat this, there is a 95% chance the mean falls here."

---

## 📦 Whisker Plots (Box Plots)

Whiskers provide a visual summary of the range and distribution of a dataset.

### Anatomy of a Box-and-Whisker

1. **The Whiskers:** Extend to the Min and Max values (or $1.5 \times \text{IQR}$).
2. **The Box:** Represents the **Interquartile Range (IQR)**—the middle 50% of data.
3. **The Median:** The horizontal line cutting through the box.
4. **Outliers:** Points plotted beyond the whiskers.

---

## How to Interpret Overlap

- **No Overlap:** If error bars between two groups do not overlap, the difference is likely **statistically significant**.
- **Large Overlap:** If error bars overlap significantly, the difference between groups is likely due to **random chance**.

---

## Checklist for Clear Charts

- [ ] Does the legend state what the error bars represent (SD vs. SEM)?
- [ ] Are outliers clearly marked on the whisker plot?
- [ ] Is the Y-axis scaled appropriately to show the bars clearly?

---

# The Importance of Normal Distribution

The **Normal Distribution** is a probability distribution that is symmetric about the mean, showing that data near the mean are more frequent in occurrence than data far from the mean.

## Why Data Scientists Care

### 1. Predictability (The Empirical Rule)

Knowing that 95% of your data exists within 2 standard deviations allows for:

- **Risk Assessment:** Predicting the likelihood of extreme events.
- **Quality Control:** Identifying when a process has "drifted" too far from the average.

### 2. Standardizing Data ($Z$-Scores)

Normal distribution allows us to compare "apples to oranges" by converting different units into $Z$-scores.
$$Z = \frac{x - \mu}{\sigma}$$
_This is essential for machine learning models that handle multiple types of data (e.g., comparing Age in years to Income in dollars)._

### 3. Foundation for Inference

Most inferential statistics (drawing conclusions about a population from a sample) rely on the **Central Limit Theorem**. Without the Normal Distribution, we couldn't reliably use a sample of 1,000 people to predict the behavior of 1,000,000.

---

## Common Real-World Examples

- **Human Traits:** Height, weight, and IQ scores.
- **Finance:** Stock market returns (over long periods) and log-returns.
- **Measurement Errors:** Errors made by physical instruments in labs.

---

## What to do if data is NOT normal?

- [ ] **Log Transformation:** Helps "squash" long tails.
- [ ] **Square Root Transformation:** Often used for count data.
- [ ] **Box-Cox Transformation:** A mathematical way to find the best power transformation to reach normality.

---

# How to Normalize and Scale Data

In Data Science, "Normalization" ensures that all input features contribute equally to the model and meet statistical assumptions.

## 🛠 Available Methods

### 1. Min-Max Scaling

- **Goal:** Fit everything into a [0, 1] range.
- **Python (Scikit-Learn):** `MinMaxScaler()`
- **When to use:** When you know the bounds of your data (e.g., image pixels 0-255).

### 2. Standardization (Z-Score)

- **Goal:** Center data at 0 with unit variance.
- **Python (Scikit-Learn):** `StandardScaler()`
- **When to use:** For most Machine Learning algorithms (SVM, Regression).

### 3. Log Transformation

- **Goal:** Fix right-skewness.
- **Formula:** `np.log(x)`
- **When to use:** When data spans several orders of magnitude (e.g., wealth distribution).

---

## Which method should I choose?

- [ ] **Is your data skewed?** Use Log or Box-Cox transformation first.
- [ ] **Are there outliers?** Use `RobustScaler` or `StandardScaler`.
- [ ] **Are you using Deep Learning?** Use `MinMaxScaler` for input layers.
- [ ] **Are you using K-Means clustering?** Use `StandardScaler` (distance-based).

---

## skewness and kurtosis

---

# Comparison of Scaling and Normalization Methods

This table provides a quick reference for choosing the correct data transformation technique based on the range requirements and the presence of outliers.

---

## Comparison Table

| Method            | Output Range | Handles Outliers? | Changes Shape? |
| :---------------- | :----------- | :---------------- | :------------- |
| **Min-Max**       | `[0, 1]`     | ❌ Poorly         | No             |
| **Z-Score**       | `[-∞, +∞]`   | ✅ Well           | No             |
| **Log Trans**     | `[0, +∞]`    | ✅ Greatly        | ✅ Yes         |
| **Robust Scaler** | Variable     | 💎 Best           | No             |

---

## Key Takeaways

### 1. When to use Min-Max

Use this when you need a bounded range (like 0 to 1) for algorithms that don't handle large values well, such as **Neural Networks** or **Image Processing**. Avoid if you have extreme outliers, as they will "squash" the normal data into a tiny range.

### 2. When to use Z-Score (Standardization)

The "default" choice for most **Linear Models** (Linear Regression, Logistic Regression) and **Support Vector Machines**. It assumes the underlying data is Gaussian (Normal).

### 3. When to use Log Transformation

Essential for **Skewed Data**. If your data has a "long tail" (like income or house prices), the Log Transform changes the shape to make it more normally distributed.

### 4. When to use Robust Scaler

If your dataset is "dirty" with many **outliers** that you cannot remove, the Robust Scaler is best because it uses the **Median** and **Interquartile Range (IQR)** rather than the Mean and Standard Deviation.

---

_File: normalization_comparison.md_

---

# Shapiro-Wilk Test for Normality

The **Shapiro-Wilk test** is a frequentist statistical test used to check whether a sample $x_1, ..., x_n$ comes from a normally distributed population.

## Interpretation of Results

The test produces a **W-statistic** and a **p-value**.

| p-value    | Interpretation          | Action                                  |
| :--------- | :---------------------- | :-------------------------------------- |
| **> 0.05** | Data appears **Normal** | Use Parametric tests (T-test, ANOVA)    |
| **≤ 0.05** | Data is **Non-Normal**  | Use Non-parametric tests (Mann-Whitney) |

---

## Usage Scenarios

### 1. Pre-analysis Check

Before running a Linear Regression, run Shapiro-Wilk on your residuals to ensure the model assumptions are met.

### 2. Small to Medium Datasets

It is most effective for sample sizes between **3 and 50**. For very large datasets, use visual checks like Q-Q plots alongside the test.

---

## Implementation (Python Example)

```python
from scipy.stats import shapiro

data = [0.873, 2.817, 0.121, -0.945, -0.055, 1.436, 0.360, -1.478, -1.637, -1.869]
stat, p = shapiro(data)

print(f'Statistics={stat:.3f}, p={p:.3f}')

if p > 0.05:
    print('Sample looks Gaussian (fail to reject H0)')
else:
    print('Sample does not look Gaussian (reject H0)')


```

---

# D'Agostino's K^2 Test

**D'Agostino's $K^2$ test** is an omnibus test for normality. It is designed to detect departures from normality by measuring the skewness and kurtosis of a dataset.

## The Mathematical Components

The test calculates the **$Z$-score** for skewness ($s$) and the **$Z$-score** for kurtosis ($k$):
$$K^2 = Z^2_s + Z^2_k$$

## Interpretation

| p-value          | Result               | Meaning                                            |
| :--------------- | :------------------- | :------------------------------------------------- |
| **$p > 0.05$**   | Fail to Reject $H_0$ | The data is consistent with a normal distribution. |
| **$p \le 0.05$** | Reject $H_0$         | The data is significantly non-normal.              |

---

## Advantages

- **Informative:** Because it's based on skewness and kurtosis, if the test fails, you know _why_ (e.g., your data is too skewed).
- **Robustness:** Performs better than Shapiro-Wilk on large datasets ($n > 1000$) where Shapiro-Wilk becomes over-sensitive.

---

## Python Implementation (SciPy)

```python
from scipy.stats import normaltest

# Example data
data = [1.2, 1.5, 1.3, 1.8, 2.0, 1.9, 1.4, 1.6, 1.7, 2.1, 2.2, 1.1, 1.5, 1.6, 1.9, 2.0, 1.4, 1.8, 1.5, 1.6]

# Perform D'Agostino's K^2 Test
stat, p = normaltest(data)

print(f'K^2 Statistic: {stat:.3f}, p-value: {p:.3f}')

if p > 0.05:
    print("Likely Normal")
else:
    print("Likely Not Normal")
```

---

# Anderson-Darling (A-D) Test

The **Anderson-Darling test** is a statistical test used to determine if a sample of data comes from a specific distribution (most commonly the Normal distribution).

## Key Characteristic: "Tail Sensitivity"

While other tests focus on the center of the data, the A-D test is designed to be **more sensitive to the tails**. This makes it ideal for fields where extreme values are critical (e.g., insurance, safety engineering).

---

## Interpretation Table

To interpret the A-D test, compare the **A2 Statistic** against the **Critical Value** for your desired alpha level (usually 0.05).

| Condition               | Result               | Conclusion                                 |
| :---------------------- | :------------------- | :----------------------------------------- |
| **A2 > Critical Value** | Reject $H_0$         | Data does **not** follow the distribution. |
| **A2 < Critical Value** | Fail to Reject $H_0$ | Data **follows** the distribution.         |

---

## Pros and Cons

### Pros

- Extremely powerful and sensitive.
- Can be used for distributions other than Normal (e.g., Weibull, Exponential, Logistic).
- More reliable than the Kolmogorov-Smirnov test.

### Cons

- Critical values must be calculated for each specific distribution type.
- Can be "too sensitive" for very large datasets, flagging tiny deviations.

---

## Python Implementation (SciPy)

```python
from scipy.stats import anderson

data = [0.873, 2.817, 0.121, -0.945, -0.055, 1.436, 0.360, -1.478, -1.637, -1.869]
result = anderson(data)

print(f'Statistic: {result.statistic:.3f}')

for i in range(len(result.critical_values)):
    sl, cv = result.significance_level[i], result.critical_values[i]
    if result.statistic < cv:
        print(f'At {sl}% level: Data looks Normal (fail to reject H0)')
    else:
        print(f'At {sl}% level: Data looks Non-Normal (reject H0)')

```

---

# Primary vs. Secondary Data

Understanding the source of your data is critical for determining the reliability and scope of your analysis.

## 🟢 Primary Data

> **"First-hand" information collected for a specific purpose.**

### Pros

- **Specific:** Addresses your exact research question.
- **Control:** You control the methodology and definitions.
- **Ownership:** The data belongs to you/your organization.

### Cons

- **Expensive:** Costs associated with tools, participants, and labor.
- **Time-consuming:** Requires a full collection cycle.

---

## 🔵 Secondary Data

> **"Second-hand" information that already exists elsewhere.**

### Pros

- **Speed:** Available immediately for analysis.
- **Cost:** Often free or significantly cheaper than primary collection.
- **Scale:** Access to massive datasets (like the Census) that would be impossible for one person to collect.

### Cons

- **Lack of Control:** You don't know exactly how the data was cleaned or handled.
- **Outdated:** The data might be several years old.
- **Fit:** It may not contain the exact variables you need.

---

## Selection Checklist

- [ ] **Budget:** If $0, use Secondary.
- [ ] **Urgency:** If needed today, use Secondary.
- [ ] **Uniqueness:** If the question has never been asked, use Primary.
- [ ] **Accuracy:** If high precision is required, use Primary.

---

# Data Types by Source: Primary vs. Secondary

This file breaks down the technical formats and states of data depending on whether it is sourced first-hand or second-hand.

## 🟢 Primary Data: The Raw State

Primary data is **unprocessed**. It is the "atomic" unit of information.

- **Format Type:** Often semi-structured or unstructured.
- **Data State:** Raw. It contains all original noise, errors, and outliers.
- **Examples:** \* Individual responses to a questionnaire.
  - Raw log files from a website server.
  - Video footage from a security camera.

## 🔵 Secondary Data: The Compiled State

Secondary data is **processed**. It is data that has been "digested" by another entity.

- **Format Type:** Highly structured.
- **Data State:** Refined. It is often aggregated (sums, averages, or counts).
- **Examples:**
  - A census report showing "Population by City" (rather than individual names).
  - Financial statements (Balance sheets, P&L).
  - Industry trend reports from agencies like Gartner or McKinsey.

---

## Technical Summary

| Technical Aspect | Primary                  | Secondary                  |
| :--------------- | :----------------------- | :------------------------- |
| **Granularity**  | Atomic (Single points)   | Aggregate (Grouped points) |
| **Cleaning**     | Required (Manual/Code)   | Pre-cleaned (Usually)      |
| **Integrity**    | You verify it            | You trust the source       |
| **Flexibility**  | High (Can re-categorize) | Low (Fixed categories)     |

---

[https://archive.ics.uci.edu/](https://archive.ics.uci.edu/)

[https://datasetsearch.research.google.com/](https://datasetsearch.research.google.com/)