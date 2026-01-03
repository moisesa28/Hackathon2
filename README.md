# Hackathon2
# Trustpilot Sentiment Analysis (Pet Products)

## Project Overview
This project analyzes Trustpilot customer reviews for pet products to understand:
- What drives negative sentiment
- Whether complaints are one-time or recurring
- How machine learning compares to rule-based sentiment analysis

The goal is to translate unstructured customer feedback into actionable business insights.

## Approach
1. Text preprocessing and normalization
2. Rule-based sentiment classification using a domain-specific dictionary
3. Complaint theme identification
4. Repeat reviewer analysis
5. Naïve Bayes sentiment classification
6. Comparison between rule-based and ML predictions

## Key Findings
- Customer support failures are the most common driver of negative reviews
- Food safety complaints are less frequent but high severity
- ~85% of negative reviews come from one-time reviewers
- ~15% come from repeat reviewers, indicating unresolved issues
- Machine learning agrees with rule-based sentiment in most cases
- Disagreements occur mainly in mixed or recovery reviews

## Tools Used
- Google Sheets
- Python (pandas, scikit-learn)
- Naïve Bayes (MultinomialNB)

## Limitations
- No star ratings available
- Sentiment labels generated via rule-based logic
- Repeat reviewers inferred from normalized display names

## Files
- `/notebooks` — analysis notebooks
- `/visuals` — exported charts
- `/slides` — final presentation

## Author
Moises Alcahe
