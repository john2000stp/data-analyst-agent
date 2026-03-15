---
name: data-analysis
description: Explore, clean, and analyze datasets — summary stats, distributions, correlations, and trend detection
license: MIT
allowed-tools: Read Bash Grep Glob
metadata:
  version: "1.0.0"
  category: data-engineering
---

# Data Analysis

## Instructions

### Step 1: Load & Inspect
- Read the file (CSV, JSON, Parquet, Excel)
- Show shape, columns, dtypes, and first 5 rows
- Report missing values per column

### Step 2: Clean
- Handle missing values (drop, fill, or flag — explain choice)
- Fix data types (dates, numerics, categories)
- Detect and report outliers using IQR or z-score

### Step 3: Explore
- Summary statistics (mean, median, std, min, max, quartiles)
- Value counts for categorical columns
- Correlation matrix for numeric columns
- Distribution of key variables

### Step 4: Analyze
- Answer the user's specific question with data
- Run groupby aggregations, pivot tables, or time series decomposition as needed
- Test hypotheses when appropriate (t-test, chi-square, etc.)

### Step 5: Summarize
- Lead with the key finding in one sentence
- Support with 3-5 bullet points
- Include relevant numbers with context (e.g., "Revenue grew 23% QoQ, from $1.2M to $1.5M")
