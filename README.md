# 🎵 Music and Mental Health  
*Data Programming Project*  
Author: **Elena Dameska**

## 📌 Project Overview

This project explores the relationship between music preferences and mental health using the **Music and Mental Health (MxMH)** dataset. Music is known to influence emotions, but the impact of specific genres on mental well-being is still not fully understood. This analysis aims to identify potential patterns between genre preferences and self-reported levels of anxiety, depression, and stress. You can view this project [here](https://coruscating-marshmallow-94c788.netlify.app/)

## 📂 Table of Contents

1. [Introduction and Problem Description](#1-introduction-and-description-of-the-problem)  
2. [Presentation of the Data](#2-presentation-of-the-data)  
3. [Transformation of Data](#3-transformation-of-data)  
4. [Exploratory Data Analysis](#4-exploratory-data-analysis)  
5. [Conclusion](#5-conclusion)  
6. [References](#6-references)

---

## 1. Introduction and Description of the Problem

Music is widely used as a tool for emotion regulation and stress relief. While music therapy is a recognized method in mental health care, it’s still unclear how different genres affect individuals with various mental health conditions.

The goal of this project is to analyze whether people who prefer certain music genres report higher or lower levels of **anxiety**, **depression**, and **stress**.

---

## 2. Presentation of the Data

- **Dataset:** `mxmh_survey_results.csv` (736 responses, 33 columns)  
- **Key variables:**  
  - `age`, `fav_genre`, `hours_per_day`, `anxiety`, `depression`, `music_effects`, etc.  
  - Frequency of listening to 16 different genres  
- **Libraries used:** `tidyverse`, `janitor`, `skimr`, `gt`  
- Data includes a mix of categorical and numerical variables.  
- Most participants are aged **18–25**, with one participant over 80.

---

## 3. Transformation of Data

- Cleaned column names using `janitor::clean_names()`
- Filtered out invalid ages
- Recoded some variables for consistency
- Handled missing values

---

## 4. Exploratory Data Analysis

- Distribution of mental health scores by genre preference
- Correlation between hours of listening and anxiety/depression/stress
- Genre effect ratings visualized with `ggplot2`
- Age distribution and other demographic insights

---

## 5. Conclusion

- Rock, EDM, and metal genres show higher reported anxiety levels
- Lo-fi, classical, and oldies are linked with more positive mental effects
- Music appears to support emotional regulation, especially for stress relief
- Self-reporting and sampling bias limit generalization

---

## 6. References

- MxMH dataset: [Kaggle - Music & Mental Health](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)
