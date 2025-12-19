# Norwegian Cruise Line – Guest Experience Analytics

## Project Overview
This project analyzes large-scale guest feedback from Norwegian Cruise Line using Natural Language Processing (NLP) techniques to evaluate guest sentiment and identify key drivers of dissatisfaction across ship classes.

The objective is to convert unstructured customer comments into actionable business insights that can support guest experience, operations, and strategic decision-making.

---

## Business Questions Addressed
- How does guest sentiment vary across ship classes?
- Which ship classes underperform relative to expectations?
- What are the primary drivers of negative guest experiences?
- Where should improvement efforts be prioritized for maximum impact?

---

## Analysis 1: Sentiment Analysis by Ship Class
- Applied VADER sentiment analysis to 400,000+ guest comments
- Generated sentiment scores ranging from -1 (very negative) to +1 (very positive)
- Compared average sentiment and negative feedback rates across ship classes
- Identified best-performing and underperforming ship classes

**Key Insight**
Premium and flagship ship classes show higher expectation sensitivity, while certain legacy ships demonstrate lower and more inconsistent sentiment.

---

## Analysis 2: Theme / Driver Analysis of Negative Feedback
- Isolated negative sentiment comments to focus on dissatisfaction drivers
- Tokenized and processed text using NLP techniques
- Grouped keywords into business-relevant themes:
  - Food & Dining
  - Service Quality
  - Cabin Experience
  - Excursions & Ports
- Calculated percentage distribution of complaint themes by ship class

**Key Insight**
Food & Dining is the dominant dissatisfaction driver across all ship classes, followed by Service Quality. Cabin Experience issues are more prominent in older or flagship ships.

---

## Tools & Technologies
- Python (Pandas, NLTK)
- Google Colab
- Power BI (dashboard design)
- PowerPoint (executive presentation)

---

## Repository Structure
