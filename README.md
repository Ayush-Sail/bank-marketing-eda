# Bank-Marketing-EDA


# Exploratory Data Analysis (EDA) in Banking Using Python

A hands-on data analysis project that applies the Pandas framework to real-world banking data — uncovering client behavior patterns and informing smarter marketing strategies.

---

## Overview

This project walks through a complete exploratory data analysis (EDA) pipeline on a bank marketing dataset. The goal is to understand what drives client responses to direct call campaigns, with a focus on term deposit subscriptions.

The analysis covers everything from raw dataset exploration to pivot tables and rich visualizations — providing actionable insights for bank scoring and campaign planning.

---

## Objectives

- Explore a real-world banking dataset using the Pandas framework
- Build pivot tables to surface key statistics across client segments
- Visualize data distributions and relationships using multiple plot types

---

## Key Questions Explored

- What share of clients were successfully converted in the dataset?
- What are the average values of numerical features among converted clients?
- What is the typical call duration for clients who subscribed?
- What is the average age among converted, unmarried clients?
- How do average age and call duration vary across different employment types?

---

## Dataset

**Source:** [UCI Machine Learning Repository — Bank Marketing Dataset](https://archive.ics.uci.edu/ml/citation_policy.html)

This is a publicly available dataset used for research purposes. It represents a subset of direct marketing campaign data from a Portuguese banking institution.

> Moro, S., Cortez, P., & Rita, P. (2014). A data-driven approach to predict the success of bank telemarketing. *Decision Support Systems*, 62, 22–31.

---

## Project Outline

1. **Materials & Methods** — Dataset background and problem framing
2. **General Analysis**
   - Library imports and environment setup
   - Dataset exploration (shape, types, missing values, distributions)
   - Pivot table construction
   - Visualization with Pandas
3. **Tasks** — Answering targeted business questions through code

---

## Tech Stack

| Library | Purpose |
|---|---|
| `NumPy` | Numerical operations and array handling |
| `Pandas` | Data loading, cleaning, transformation, and pivot tables |
| `Matplotlib` | Static visualizations and plot customization |

---

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib
   ```
3. Open the notebook and run cells sequentially

---

## References

- [UCI ML Repository Citation Policy](https://archive.ics.uci.edu/ml/citation_policy.html)
- Moro et al., 2014 — *A data-driven approach to predict the success of bank telemarketing*
