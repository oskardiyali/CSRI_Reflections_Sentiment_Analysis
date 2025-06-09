# Sentiment Analysis of Student Reflections

This project performs a sentence-level sentiment analysis of student-written reflections using two lexicon-based methods in R: **AFINN** and **NRC**. The goal is to explore the emotional tone and affective content within responses to a shared academic reflection prompt.

---

## Project Summary

- **Dataset**: 20 student responses(sample) to a common reflection question.
- **Prompt**: *"Sample Prompt: What did you learn or experience from this task?"*
- **Tech Stack**: R, tidyverse, tidytext, syuzhet, ggplot2

---

## Objectives

- Tokenize reflections at the **sentence level** for more granular sentiment detection.
- Score each sentence using the **AFINN** lexicon (numerical polarity).
- Classify emotion types using the **NRC** lexicon (e.g., joy, fear, trust).
- Visualize the **distribution of sentiment scores** and **emotion categories**.
- Identify the **most positive sentences** and common emotional patterns.

>  *Note: This version reflects the first full implementation. Further guidance from the supervising professor may refine or shift the analytical direction (e.g., comparing sentiment by question or student).*

---

## File Structure

```
CSRI_Reflections_Sentiment_Analysis/
│
├── data/
│   └── student_reflections_with_question_long.csv
│   └── student_reflections_with_question_long.csv
│   └── student_reflections_with_question_long.csv
├── Sentiment_CSRI.Rmd # Main RMarkdown analysis file
├── Sentiment_CSRI.html # Rendered HTML report (optional)
├── README.md # Project overview and documentation
├── .gitignore # Files excluded from Git

```


---

##  Sample Visuals

- Histogram of sentiment scores (AFINN)
- Top 5 most positive sentences
- Emotion frequency barplot (NRC)

---

##  Preliminary Insights

- **Joy** and **trust** appear most frequently across reflections.
- **Positive sentiment** often aligns with experiences involving growth, support, or overcoming challenges.
- A few reflections contain **negative or mixed emotions**, often related to difficult transitions or academic struggles.

---

**Developed by Oskar Diyali**  
Cornell College | 2025  
GitHub: [github.com/oskardiyali](https://github.com/oskardiyali)

