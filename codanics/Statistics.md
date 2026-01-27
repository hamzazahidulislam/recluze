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
