# Sentiment Analysis of Student Reflections

This project analyzes student-written reflections to identify emotional tone and intensity using two popular sentiment analysis methods in R: AFINN and NRC. The goal is to explore how students emotionally respond to academic tasks and to visualize sentiment trends across responses.

---

## Project Overview

- **Dataset**: Student responses to the same reflection prompt.
- **Prompt**: 
- **Tech Stack**: R, tidyverse, tidytext, syuzhet, ggplot2

---

##  Objectives

- Tokenize and score student reflection responses at the sentence level.
- Identify the most positive statements using AFINN sentiment values.
- Classify emotional content using NRC emotion categories (e.g., joy, trust, sadness).
- Visualize sentiment distribution and emotional themes.

---

##  File Structure

```
student-sentiment-analysis/
│
├── student_reflections_with_question_long.csv
├── sentiment_analysis.Rmd   # R Markdown notebook with full analysis
├── sentiment_analysis.html  # Rendered HTML output (if knitted)
├── README.md                # Project overview and documentation
```

---

##  Sample Visuals

- Histogram of sentiment scores using AFINN
- Top 5 most positive student sentences
- Emotion breakdown (joy, anger, trust, etc.) using NRC

---

##  Insights

- Positive sentiments were often tied to achievement, growth, and support.
- Some reflections also expressed frustration or anxiety depending on task complexity.
- Joy and trust were the most common emotions observed overall.

---

Developed by Oskar Diyali as part of an academic research initiative in text analysis and educational data mining.
