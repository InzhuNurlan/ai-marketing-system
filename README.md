# AI Marketing Intelligence System
## Team Members

- Nazerke @nazhmdt
- Inzhu @InzhuNurlan

## Professor
- Mohamed Ali Ibrahim @Moali123-svg

## Project Description

This project presents an AI-driven marketing decision system for the AI for Marketing Decisions course. The system helps a company understand customer behavior, segment customers, predict campaign response, personalize product recommendations, and analyze customer sentiment.

The project combines Python analytics, machine learning, recommendation logic, NLP, and Power BI dashboards to support data-driven marketing decisions.

## Team Members

- Nazerke Zhumadilova
- Inzhu Nurlan

## Course Information

- Course: AI for Marketing Decisions
- Group: AIB-2401
- Professor: Mohamed Ali Ibrahim
- Specialty: AI in Business

## Datasets Used

### 1. Customer Personality Analysis

Source: Kaggle  
Link: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

This dataset includes customer demographics, income, spending behavior, purchase channels, campaign responses, and registration dates. It was used for customer analytics, segmentation, prediction, recommendation, and Power BI visualization.

### 2. 171k Product Review with Sentiment Dataset

Source: Kaggle  
Link: https://www.kaggle.com/datasets/mansithummar67/171k-product-review-with-sentiment-dataset

This dataset includes product names, prices, ratings, reviews, summaries, and sentiment labels. It was used for NLP sentiment analysis and customer feedback insights.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- WordCloud
- Power BI Service
- GitHub

## Machine Learning and AI Methods

- K-Means Clustering
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- TF-IDF Vectorizer
- Cosine Similarity
- Sentiment Classification
- Recommendation System

## Project Objectives

The main objective is to build an AI-based marketing intelligence system that helps a company:

- Understand customer behavior
- Identify customer segments
- Predict campaign response
- Recommend personalized product categories
- Analyze customer sentiment
- Support marketing decisions through Power BI

## Project Structure

ai-marketing-system/
│
├── README.md
├── ai_marketing_decision_system.ipynb
├── marketing_campaign.csv
├── AI_Marketing_final_InzhuNazerke.pbix
├── AIMD_final_Nazerke_Inzhu_presentation.pdf
├── screenshots_InzhuNazerke.pdf
│
├── ai for marketing-files for powerbi/
│   ├── powerbi_customer_final.csv
│   ├── powerbi_recommendation_output.csv
│   ├── powerbi_sentiment_output.csv
│   ├── powerbi_model_comparison.csv
│   ├── powerbi_category_sentiment.csv
│   ├── powerbi_segment_summary.csv
│   └── powerbi_recommendation_by_segment.csv

## Analytical Workflow

### 1. Data Cleaning and Feature Engineering

The project started with cleaning and preparing the customer and review datasets. Missing values were handled, duplicate rows were removed, date columns were converted into the correct format, and unrealistic outliers were filtered out.

New marketing features were created:

- Customer Lifetime Value
- Total Spending
- Total Purchases
- Average Order Value
- Purchase Frequency
- Days Since Last Purchase
- Customer Tenure
- Campaign Acceptance
- Family Size
- Parent Status

These features were later used for customer segmentation, predictive modeling, recommendations, and Power BI dashboards.

### 2. Exploratory Data Analysis

Exploratory data analysis was used to understand customer behavior and marketing patterns. The analysis included spending trends, customer demographics, campaign response rates, VIP customers, and correlation between important marketing variables.

Main findings from EDA:

- Higher-income customers usually spend more.
- Total spending is strongly connected with total purchases.
- Some customers visit the website often but spend little.
- Campaign response differs across customer groups.
- A small group of VIP customers creates strong revenue opportunities.

### 3. Customer Segmentation

K-Means Clustering was used to divide customers into meaningful marketing segments. The Elbow Method was used to choose the final number of clusters.

The final customer segments were:

- Budget Browsers
- High-Value Loyalists
- Family-Oriented Regular Customers

Each segment was analyzed by income, age, spending, purchases, campaign acceptance, website visits, and customer behavior. Marketing strategies were then created for each group.

### 4. Predictive Customer Behavior Model

The project predicted whether a customer would respond to a marketing campaign. Three models were compared:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

The models were evaluated using accuracy, precision, recall, F1 score, and confusion matrix. Logistic Regression was selected as the final model because it performed better at identifying actual campaign responders based on F1 score and recall.

### 5. Recommendation System

A product category recommendation system was created using cosine similarity. Since the customer dataset does not include individual product IDs, the system recommends product categories.

Recommended categories include:

- Wines
- Fruits
- Meat Products
- Fish Products
- Sweet Products
- Gold Products

The system finds customers with similar purchasing behavior and recommends categories where similar customers spend more. This supports cross-selling, personalization, and average order value improvement.

### 6. Sentiment Analysis

Sentiment analysis was performed using the product review dataset. A Natural Language Processing pipeline was built using TF-IDF and Logistic Regression.

Reviews were classified as:

- Positive
- Negative
- Neutral

The sentiment model achieved approximately 88% accuracy. Word clouds and product category sentiment analysis were used to understand what customers like and what problems they mention in negative reviews.

## Power BI Dashboard

The final Power BI report contains 8 dashboard pages.

### Page 1 — Executive Marketing Overview

This page gives a high-level summary of the marketing system. It includes total revenue, total customers, average CLV, average order value, response rate, customer segments, and revenue trends.

### Page 2 — Customer Segmentation Dashboard

This page visualizes K-Means clustering results. It shows customer segments on a scatter plot, segment size, revenue by segment, and customer profile metrics.

### Page 3 — Predictive Analytics Dashboard

This page presents the machine learning model results. It includes model comparison, response probability by segment, predicted campaign response, and customer response ranking.

### Page 4 — Personalization and Recommendation Dashboard

This page shows the recommendation system results. It includes top recommended product categories, recommendation scores, personalization value, and recommendations by customer segment.

### Page 5 — Campaign Performance Dashboard

This page analyzes campaign effectiveness. It shows campaign response rates, campaign acceptance by segment, response probability, and spending trends.

### Page 6 — Sentiment and Social Media Dashboard

This page presents NLP sentiment analysis results. It includes sentiment distribution, sentiment by product category, word cloud analysis, rating analysis, and customer feedback insights.

### Page 7 — Ethics, Privacy and Risk Dashboard

This page addresses responsible AI use. It includes data privacy considerations, bias monitoring, transparency of model logic, and the main ethical risks of AI-based marketing.

### Page 8 — AI Marketing Strategy and Recommendations

This page summarizes the final business recommendations. It includes top insights, budget reallocation logic, 90-day roadmap, and the business value of the AI marketing system.

## Power BI Files

The following files were prepared and used for Power BI:

- powerbi_customer_final.csv
- powerbi_recommendation_output.csv
- powerbi_sentiment_output.csv
- powerbi_model_comparison.csv
- powerbi_category_sentiment.csv
- powerbi_segment_summary.csv
- powerbi_recommendation_by_segment.csv

Main Power BI report file:

- AI_Marketing_final_InzhuNazerke.pbix

Dashboard screenshots:

- screenshots_InzhuNazerke.pdf

Main usage of files:

- powerbi_customer_final.csv was used for executive overview, segmentation, predictive analytics, campaign performance, ethics, and strategy pages.
- powerbi_recommendation_output.csv was used for the recommendation and personalization dashboard.
- powerbi_sentiment_output.csv was used for the sentiment analysis dashboard.
- powerbi_model_comparison.csv was used to compare Logistic Regression, Random Forest, and XGBoost.
- powerbi_category_sentiment.csv was used to show sentiment trends across product categories.
- powerbi_segment_summary.csv was used to summarize customer segment profiles.
- powerbi_recommendation_by_segment.csv was used to analyze recommended categories by segment.

## Key Business Findings

### Finding 1: High-Value Loyalists are the most valuable customer segment

High-Value Loyalists have the highest income, highest total spending, frequent purchases, and stronger campaign response. This segment should be prioritized with VIP offers, loyalty programs, premium bundles, and personalized recommendations.

### Finding 2: Campaign history is a strong predictor of future response

Previous campaign acceptance was one of the strongest predictors of future campaign response. Customers who accepted previous campaigns are more likely to respond again, so campaign history should be used for targeting.

### Finding 3: Personalization improves marketing relevance

The recommendation system showed that personalized product category recommendations can be more useful than one generic offer for all customers. This supports cross-selling, better targeting, and potential average order value improvement.

### Finding 4: Customer sentiment is mostly positive

Most product reviews were positive, which shows that the general customer mood is favorable. Positive reviews often mention good quality, nice product, and value for money.

### Finding 5: Some product categories need improvement before scaling ads

Negative reviews showed problems related to poor quality, bad experience, and money waste. Categories with higher negative sentiment should be improved before increasing advertising budget.

## Business Recommendations

1. Focus more marketing budget on High-Value Loyalists because they generate the highest value and respond better to campaigns.
2. Use the predictive model to target customers with higher response probability instead of sending campaigns to everyone equally.
3. Apply personalized product recommendations to support cross-selling and improve campaign relevance.
4. Use loyalty programs, VIP offers, and premium bundles for High-Value Loyalists.
5. Use discounts, simple offers, and retargeting campaigns for Budget Browsers.
6. Use family bundles, practical promotions, and cross-selling offers for Family-Oriented Regular Customers.
7. Promote product categories with strong positive sentiment because customers already show trust and satisfaction.
8. Improve product categories with high negative sentiment before scaling advertising campaigns.
9. Monitor AI model fairness, customer privacy, and responsible personalization.
10. Use the Power BI dashboard as a regular decision-making tool for marketing strategy.

## How to Run the Project

1. Open ai_marketing_decision_system.ipynb in Jupyter Notebook or Google Colab.
2. Upload the required datasets.
3. Run all notebook cells from top to bottom.
4. The notebook will clean data, build models, generate recommendations, run sentiment analysis, and export Power BI-ready CSV files.
5. Open the CSV files and .pbix file in Power BI Service to view the dashboard.

## Main Results

- Customer dataset after cleaning: 2,236 records
- Sentiment dataset after cleaning: 59,941 records
- Final customer segments: 3
- Best predictive model: Logistic Regression
- Campaign response prediction accuracy: approximately 79%
- Sentiment classification accuracy: approximately 88%
- Recommendation system created at product category level
- Power BI dashboard created with 8 report pages

## Responsible AI Considerations

This project considers responsible AI use in marketing. The system should support human decision-making and should not fully replace marketing judgment.

Main ethical considerations:

- Customer privacy
- Bias in targeting
- Transparent model logic
- Responsible personalization
- Regular model monitoring
- Avoiding unfair customer exclusion

## Conclusion

This project shows how AI can support marketing decisions by combining customer analytics, machine learning, recommendation systems, sentiment analysis, and Power BI.

The system helps answer four key questions:

1. Who are our customers?
2. Which customers are likely to respond?
3. What should we recommend to each customer?
4. What do customers think about our products?

Overall, the AI Marketing Intelligence System helps improve targeting, reduce wasted marketing budget, personalize customer communication, and support data-driven strategy.
