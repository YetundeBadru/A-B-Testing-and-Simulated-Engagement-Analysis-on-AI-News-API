# A-B-Testing-and-Simulated-Engagement-Analysis-on-AI-News-API
### Which Headline Works Better?  
### A/B Testing and Simulated Engagement Analysis on AI News Headlines

---

## Project Summary  
This project investigates how headline characteristics such as content length, publication source, headlines, and posting time influence audience engagement in Artificial Intelligence news articles. Using real-world data collected via NewsAPI, the analysis simulates user engagement trends and performs A/B testing to derive actionable insights.

---

## Problem Statement  
In the digital media space, news outlets compete for reader attention, especially on hot topics like Artificial Intelligence (AI). Engagement is influenced by factors such as headline length, timing, and source. This project aims to explore which combinations of these elements perform better in capturing reader interest.

---

## Objectives

- Collect and preprocess news article data using NewsAPI.
- Simulate user engagement based on headline length and publishing time.
- Apply statistical analysis (t-tests, boxplots) to Compare performance between groups.
- Identify influential features in headline engagement
- Visualize findings and interpret A/B testing results.

---

## Tools & Technologies
- **Languages:** Python
- **Libraries:** pandas, numpy, scipy, matplotlib, seaborn, requests
- **Environment:** Jupyter Notebook
- **Data Source:** [NewsAPI](https://newsapi.org/)
- **Query:** Articles containing the keyword *"Artificial Intelligence"*  
- **Fields Collected:** Headline, publication source, publication time, headline length

---

## Methodology
The analysis follows a simulated A/B testing framework to compare two distinct groups of articles:
- Group A (Control): Articles published during the morning hours (e.g., 6:00 AM - 12:00 PM).
- Group B (Test): Articles published during the evening hours (e.g., 6:00 PM - 12:00 AM).

The methodology includes:
1. **Data Acquisition**
   - Installed and Imported Libraries
   - API key Setup
   - API Request and Data Fetching (Used NewsAPI to fetch 100 recent articles with metadata such as title, source, and publishing time).
   - Converted to DataFrame
   - Data storage to .csv file

3. **Data Preparation:**
   Cleaned and prepared the fetched data for statistical analysis.
   - Data Loading
   - Column Selection
   - Data Type Conversion
   - Feature Engineering
   - Handling Missing Values
   - Descriptive Analysis

4. **A/B Grouping:**
   - Group Assignment Logic based on time of publication
   - Group Distribution based on time of publication

5. **Simulated Engagement**
   - Created a synthetic engagement score using normal distribution influenced by:
     - Headline length
     - Time of publication
     - Source
     - Random noise

6. **A/B Testing**
   - Performed independent t-tests to compare:
     - Long vs. short headlines
     - Morning vs. evening publication groups

7. **Visualization**
   - Boxplots and histograms were used to illustrate group differences and distribution spread.
   - Generated Word Clouds for each cohort's headlines to visually compare recurring themes and keywords.

---

## Key Insights  
- Quantitative Results:
  The t-test results reveal whether the difference in article content length between morning and evening publications is statistically significant, providing a data-driven insight into publication strategy.
- Qualitative Insights:
  Visual analysis of word clouds highlights key differences in terminology and focus for headlines published in the morning versus the evening, suggesting potential engagement strategies for different times of day.

---

## Conclusion 
The findings provide actionable insights into how publication timing can be optimized to influence content engagement, offering a foundational framework for a data-driven content strategy.


## How to Run  
1. Clone this repository  
2. Install required packages:  
```bash
   <<< pip install pandas matplotlib seaborn newsapi-python >>>



 Documentation
Full project documentation with background, objectives, methods, results, and discussion is available within the notebook and linked below:
🔗 Project Documentation (Replace with your final GitHub URL)

👩🏽‍💻 Author
Yetunde Badru
Data Scientist | AI/ML Enthusiast
📫 LinkedIn (Optional)
