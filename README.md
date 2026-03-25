# Food products sales
This project analyzes user behavior in a food delivery startup application. It explores the sales funnel to identify where users drop off before purchase and evaluates an A/A/B test to measure the impact of new font designs. The analysis compares control and test groups to determine whether the design change affects conversion rates.

User Behavior Funnel Analysis and A/A/B Testing for Mobile App Design Optimization
Technologies: Python | Pandas | NumPy | Matplotlib | Statistical Analysis | A/B Testing | EDA

## Project overview 

**Business Problem**:
A startup that sells food products wants to understand user behavior within their mobile application and evaluate whether changing the app’s font design impacts conversion rates.

**My Role**:
Data Analyst performing funnel analysis and A/A/B experiment evaluation to support data-driven product design decisions.

**Dataset**:
User event logs including event names, timestamps, unique user IDs, and experiment group assignments (two control groups and one test group).

## Data Analysis & Funnel Analytics
**User journey and funnel conversion analysis**
Drop-off rate calculation between stages
Event-based behavioral analysis
Time-based user activity exploration

**A/A/B Testing & Statistics**
Control group validation (A/A test)
Hypothesis testing for experiment evaluation
Statistical significance testing
Multiple comparison analysis

**Data Cleaning & Preparation**
Duplicate user handling
Timestamp conversion
Event filtering and grouping
Experiment segmentation

## **Python Libraries Used**
```python
import pandas as pd           # Data manipulation
import numpy as np           # Numerical computations  
import matplotlib.pyplot as plt  # Data visualization
from statsmodels.stats.proportion import proportions_ztest
