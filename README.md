# TikTok Video Claim Classification

## Overview
This project focuses on building a predictive model to classify TikTok videos as containing either a claim or an opinion. By automating this classification, TikTok can streamline the moderation process, reduce backlog, and prioritize user reports more effectively.

## Dataset Information
The dataset consists of:
- Categorical, text, and numerical features.
- Metadata associated with each video.
- A `claim_status` column indicating whether a video presents a claim or an opinion.

## Key Steps
1. **Data Inspection & Analysis**
   - Reviewed the dataset structure, including numerical and non-numerical variables.
   - Identified missing values in multiple columns, including `claim_status`.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of numerical variables.
   - Identified potential outliers using standard deviation and maximum values.

3. **Hypothesis Testing**
   - Conducted statistical tests to validate assumptions.
   - Explored correlations between key variables.

4. **Regression Modeling**
   - Built regression models to analyze relationships between video metadata and claim likelihood.

5. **Machine Learning for Video Classification**
   - Implemented classification models to predict whether a video contains a claim or an opinion.
   - Evaluated model performance using accuracy, precision, recall, and F1-score.


## Results & Insights
- The model successfully differentiates between claims and opinions with high accuracy.
- Insights from EDA help improve content moderation strategies.

## Future Work
- Enhance feature engineering for better classification.
- Experiment with deep learning approaches for improved performance.

## Author
- Divya - Data Analyst

## License
This project is licensed under the MIT License - see the LICENSE file for details.

