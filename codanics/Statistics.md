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
* **Low Bias + Low Random Error:** Hits the center of the target every time.
* **High Bias + Low Random Error:** Hits a tight cluster, but far away from the center (Reliably Wrong).
* **Low Bias + High Random Error:** Scattered all over the target, but the average is the center.

---

## Prevention Strategies
- [ ] **Calibration:** Regularly test equipment against a known standard.
- [ ] **Blinding:** Use double-blind studies so researchers don't know which group is which.
- [ ] **Anonymity:** Ensure surveys are anonymous to reduce social desirability bias.
- [ ] **Standard Operating Procedures (SOPs):** Use strict scripts and protocols for all data collectors.

---