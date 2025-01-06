#Netflix Conjoint Analysis Project

Portfolio Project

Overview

This project involves performing a Choice-Based Conjoint Analysis (CBC) to help Netflix rejuvenate its streaming service growth. Unlike traditional survey methods that evaluate user preferences based on individual features, CBC analyzes consumer preferences in a holistic way, providing data-driven insights into which features or combinations of features resonate most with users.

Using Python and data analysis techniques, this project simulates a real-world business problem where market research and analytics guide product strategy and decision-making.

Objective

To determine how Netflix can enhance its platform and offerings by identifying the most appealing feature combinations to current and potential subscribers.

Key Questions Addressed:
What features matter most to Netflix subscribers (e.g., price, additional content, ad frequency)?
How do feature trade-offs impact user preferences?
What combination of features offers the most value to Netflix's target audience?
Dataset

The dataset consists of survey responses from hypothetical Netflix customers. It captures user preferences across different feature combinations, allowing us to analyze trade-offs and derive actionable insights.

Dataset Details:
customerid: A unique identifier for each respondent.
NumberAccounts: The number of streaming accounts the customer currently uses.
price: The monthly price of the plan.
ExtraContent: Additional content included in the plan (e.g., HBO, Marvel, Disney, Soccer).
ads: Ad frequency (e.g., "one_per_day", "one_per_show").
selected: Indicates whether the respondent selected this option (1 = Yes, 0 = No).
Tools and Techniques

Tools:
Python: For data processing, analysis, and visualization.
Pandas: For handling and cleaning data.
NumPy: For numerical computations.
Matplotlib & Seaborn: For visualizing results.
Scikit-learn: For statistical modeling and simulation.
Methods:
Choice-Based Conjoint Analysis: To simulate consumer decision-making and evaluate trade-offs between product features.
Market Simulation: To predict how different feature combinations impact customer preferences.
Data Visualization: To effectively communicate insights and recommendations.
Project Workflow

Problem Definition:
Understand Netflix's current challenges and objectives.
Define attributes and levels for the conjoint analysis.
Data Preparation:
Load, clean, and preprocess the survey data using Python.
Organize data to ensure compatibility with conjoint analysis methods.
Conjoint Analysis:
Analyze user preferences for each feature and their trade-offs.
Calculate part-worth utilities for price, extra content, and ad frequency.
Market Simulation:
Simulate customer choices based on various feature combinations.
Identify the optimal feature set to maximize subscriber growth.
Visualization & Recommendations:
Create clear, insightful visualizations to highlight key findings.
Provide actionable recommendations to Netflix based on the analysis.
