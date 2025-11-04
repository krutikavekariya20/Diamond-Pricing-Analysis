# Diamond Pricing Analysis Report

**Course:** MSBA 210 (2024) — Business Analytics  
**Instructor:** Chong Huang  
**University:** Eberhardt School of Business, University of the Pacific  

**Authors:**  
- Aryan Vimalbhai Shah  
- Krish Vijaykumar Modi  
- Krutika Gordhanbhai Vekariya  

---

## Table of Contents
1. [Introduction](#introduction)  
2. [Background](#background)  
3. [Data Analysis and Pivot Table](#data-analysis-and-pivot-table)  
4. [Covariance Analysis](#covariance-analysis)  
5. [Regression Analysis](#regression-analysis)  
6. [Top 30 D Color Data](#top-30-d-color-data)  
7. [Dashboard](#dashboard)  
8. [Conclusion](#conclusion)  
9. [Appendix (Raw Data)](#appendix-raw-data)  
10. [References](#references)  

---

## Introduction

This report explores the fascinating world of **diamonds**, focusing on the key attributes that determine their market value — **color, clarity, and carat weight**. To maintain consistency, all diamonds analyzed in this study have an **Ideal Cut**.

We aim to identify which characteristics most significantly affect pricing and to understand how these factors interact.  

**Research Questions:**
1. What factors cause differences in diamond prices?
2. Between color and clarity, which has a greater impact on value?

Our analysis isolates these attributes to reveal how they shape diamond valuation and consumer perception.

---

## Background

Diamonds have long symbolized **luxury, beauty, and rarity**. Their global journey — from mines to markets — intertwines economics, ethics, and environmental impact.

### Extraction and Global Distribution
- Early diamond mining began in **India**, with major discoveries later in **Brazil** and **South Africa**.
- These events reshaped global trade and fueled industrial growth.
- The industry also carries **environmental and ethical implications**, prompting calls for sustainable and fair practices.

### Ethical Issues in Diamond Trading
The term **“blood diamonds”** refers to gems mined in war zones and sold to finance conflict. The **Kimberley Process** was established to prevent such unethical trade and ensure transparent supply chains.

### Role in the Global Economy
The diamond industry:
- Contributes significantly to national economies.
- Creates employment for thousands globally.
- Shapes trends within the luxury goods market.

Understanding this background provides context for our exploration of **modern diamond valuation**.

---

## Factors Affecting Diamond Prices

Diamonds are traditionally valued based on the **Four Cs**:

### 1. Carat
- A measure of weight (1 carat = 0.2 grams).
- Larger diamonds are rarer and more expensive.

### 2. Color
- Graded from **D (colorless)** to **Z (light yellow/brown)**.
- Colorless diamonds (D–F) are the most desirable and valuable.

### 3. Clarity
- Measures internal flaws (*inclusions*) and external flaws (*blemishes*).
- Fewer imperfections mean higher clarity and greater brilliance.

### 4. Cut
- Determines a diamond’s brilliance and light performance.
- Even with the same carat, color, and clarity, a superior cut increases appeal and value.

These characteristics collectively determine a diamond’s beauty, rarity, and market price.

---

## Data Analysis and Pivot Table

We sourced data from **leading diamond retailers** including:
- [Brilliant Earth](https://www.brilliantearth.com/)
- [Blue Nile](https://www.bluenile.com/)
- [With Clarity](https://www.withclarity.com/)
- [James Allen](https://www.jamesallen.com/)

To maintain consistency:
- Only **Ideal Cut diamonds** between **0.50–0.69 carats** were considered.
- Both **natural** and **lab-grown** diamonds were analyzed.
- Prices were standardized as **price per carat**.

### Pivot Tables and Heat Maps
- Pivot tables provided structured comparisons of price vs. color and clarity.
- **Heat maps** visually highlighted price variations across categories.

#### Key Insights:
- **Lab-grown diamonds** are priced **13%–88% lower** than natural ones due to reduced production costs.
- **Natural diamonds** often sell **45%–118% above** the Rapaport Price Index because of retail markups.

---

## Covariance Analysis

| Relationship | Sample Covariance | Interpretation |
|---------------|------------------|----------------|
| **Color vs. Price per Carat (Natural)** | -659.92 | Strong negative relationship – better color grades correlate with higher prices. |
| **Clarity vs. Price per Carat (Natural)** | -2.16 | Moderate positive relationship – clearer diamonds command higher prices. |
| **Color vs. Price per Carat (Lab-made)** | -667.23 | Negative relationship, though less pronounced. |
| **Clarity vs. Price per Carat (Lab-made)** | 183.09 | Negative relationship – higher clarity sometimes linked with lower prices. |

---

## Regression Analysis

### Lab-Made Diamonds
- **Color** moderately affects price variations.  
- **Clarity** shows stronger influence — a key determinant in lab-grown diamond pricing.

### Natural Diamonds
- Both **color and clarity** are major factors.
- Higher grades command premium prices.
- Natural diamonds are **more sensitive** to changes in these attributes than lab-grown ones.

**Overall:**  
While both diamond types respond to color and clarity changes, **natural diamonds exhibit stronger price sensitivity**, making them more volatile in value.

---

## Top 30 D Color Data

For deeper insights, we analyzed the **top 30 D-color diamonds** using descriptive analytics:
- Calculated **Mean**, **Standard Deviation**, **Upper/Lower Limits**, and **Range**.
- Identified pricing trends and potential outliers.

---

## Dashboard

A dashboard was created to visualize:
- Price distribution by color and clarity.  
- Comparisons between natural and lab-grown diamonds.  
- Trends relative to the Rapaport benchmark.

---

## Conclusion

Our study reveals that:
- **Color and clarity** significantly influence diamond pricing.
- **Natural diamonds** show stronger responsiveness to attribute variations.
- **Lab-grown diamonds** offer cost efficiency but with less price variability.

These findings enhance understanding of the **diamond market’s pricing dynamics**, offering value to both consumers and industry stakeholders.

---

## Appendix (Raw Data)

### Natural Diamonds
Raw dataset of natural diamonds analyzed in this study.

### Lab-Made Diamonds
Raw dataset of lab-grown diamonds included for comparative analysis.

---

## References

- [James Allen](https://www.jamesallen.com/)  
- [Brilliant Earth](https://www.brilliantearth.com/diamond/)  
- [Rare Carat](https://www.rarecarat.com/)  
- [Blue Nile](https://www.bluenile.com/diamonds/pear-shaped)  
- [With Clarity](https://www.withclarity.com/pages/diamonds)

---
