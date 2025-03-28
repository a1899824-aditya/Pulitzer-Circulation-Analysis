# 📰 Pulitzer Prize & Newspaper Circulation Analysis

This project explores the relationship between the number of Pulitzer Prizes won by newspapers and their average circulation or percentage change in circulation from 2004 to 2013. The analysis supports decision-making for Masthead Media’s flagship newspaper, the Boston Sun-Times.

---

## 📄 Dataset
- `pulitzerRaw.csv`  
- Includes 50 major U.S. newspapers, Pulitzer prizes (1990–2014), circulation in 2004 & 2013, and percentage change.

---

## 🛠 Tools & Libraries
- R  
- tidyverse (dplyr, ggplot2, tibble)  
- Base R (lm, predict)

---

## 📊 Project Summary
- Cleaned and transformed circulation data for 2004 and 2013  
- Created two regression models:
  - Model 1: Predicts **average circulation** (log-transformed) based on number of Pulitzer prizes  
  - Model 2: Predicts **% change in circulation** based on prizes  
- Performed full diagnostic checks: linearity, homoscedasticity, residual normality, and independence  
- Visualized distributions, trends, and model fits

---

## 📈 Key Results
- Positive linear relationship between Pulitzer prizes and average circulation  
- Negative correlation between Pulitzer prizes and % change, though not always consistent  
- Strategic scenario modeling (3, 25, 50 prizes) with prediction intervals and confidence bounds  
- Final recommendation: Continue investing in investigative journalism

---

## 📁 Files
- `Assignment3_dt.Rmd`: Full code with outputs  
- `Assignment3_dt.pdf`: Rendered report  
- `pulitzerRaw.csv`: Data used

---

## 🔍 Executive Summary
Newspapers winning more Pulitzer Prizes show higher average circulation. Regression models suggest increased journalistic quality may improve readership, though with variable percentage changes. Masthead Media is advised to continue supporting investigative journalism for long-term engagement.

---

## 👤 Author
Aditya Venugopalan Nediyirippil  
GitHub: [a1899824-aditya](https://github.com/a1899824-aditya)
