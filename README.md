# Smart-Crop-Prediction
The Smart Crop Prediction project applies machine learning techniques to enhance agricultural yield forecasting. By analyzing 15+ classification and regression models, the study evaluates the impact of weather, soil properties, and agricultural practices on crop production.

Project Goals & Methodology
The goal of this project is to develop a smart crop prediction model using machine learning techniques. The project focuses on both classification and regression approaches to enhance agricultural yield forecasting.

For classification, the aim is to predict crop yield categories (0-4) while ensuring an accuracy of over 80% and identifying the key factors influencing yield. On the other hand, the regression model is designed to provide precise yield predictions (in tons per hectare), targeting an RMSE below 0.5 and an R² score above 0.9.

To ensure high-quality data, various preprocessing techniques were applied, including standardization, one-hot encoding for categorical variables, and SMOTE to address class imbalance. The original dataset had a significant imbalance, with Category C having 409,999 samples, while Category A had only 20,183. To correct this, random undersampling was applied to balance each category to 20,000 samples, creating a more uniform dataset.

Model Selection & Performance
Several machine learning models were tested to find the most effective approach. For classification, Decision Trees, Random Forest, and XGBoost were evaluated, with XGBoost emerging as the best model, achieving 81.35% accuracy and an AUC score of 0.9681.

For regression, models like Linear Regression, Ridge Regression, Lasso Regression, and XGBoost were compared. Ridge Regression performed the best, with an RMSE of 0.499 and an R² score of 0.913.

Feature Importance & Real-World Applications
The analysis highlighted key factors that significantly impact crop yield, including fertilizer usage (1.4 score), rainfall (1.3), and irrigation (1.2). Agricultural inputs were found to have the most dominant influence, while weather conditions also played a crucial role.

This model has several practical applications:

Agricultural Planning: It provides accurate yield predictions with a margin of ±0.5 tons per hectare.
Financial Forecasting: The model helps estimate potential revenue and assess risks.
Resource Optimization: It aids in strategic input planning and market forecasting.
Decision Support: Farmers can use the insights to optimize irrigation and fertilization for maximum efficiency and profitability.
This project showcases how data-driven decision-making can transform agriculture, making it more efficient, sustainable, and profitable for farmers and stakeholders alike.Project Goals & Methodology
The goal of this project is to develop a smart crop prediction model using machine learning techniques. The project focuses on both classification and regression approaches to enhance agricultural yield forecasting.

For classification, the aim is to predict crop yield categories (0-4) while ensuring an accuracy of over 80% and identifying the key factors influencing yield. On the other hand, the regression model is designed to provide precise yield predictions (in tons per hectare), targeting an RMSE below 0.5 and an R² score above 0.9.

To ensure high-quality data, various preprocessing techniques were applied, including standardization, one-hot encoding for categorical variables, and SMOTE to address class imbalance. The original dataset had a significant imbalance, with Category C having 409,999 samples, while Category A had only 20,183. To correct this, random undersampling was applied to balance each category to 20,000 samples, creating a more uniform dataset.

Model Selection & Performance
Several machine learning models were tested to find the most effective approach. For classification, Decision Trees, Random Forest, and XGBoost were evaluated, with XGBoost emerging as the best model, achieving 81.35% accuracy and an AUC score of 0.9681.

For regression, models like Linear Regression, Ridge Regression, Lasso Regression, and XGBoost were compared. Ridge Regression performed the best, with an RMSE of 0.499 and an R² score of 0.913.

Feature Importance & Real-World Applications
The analysis highlighted key factors that significantly impact crop yield, including fertilizer usage (1.4 score), rainfall (1.3), and irrigation (1.2). Agricultural inputs were found to have the most dominant influence, while weather conditions also played a crucial role.

This model has several practical applications:

Agricultural Planning: It provides accurate yield predictions with a margin of ±0.5 tons per hectare.
Financial Forecasting: The model helps estimate potential revenue and assess risks.
Resource Optimization: It aids in strategic input planning and market forecasting.
Decision Support: Farmers can use the insights to optimize irrigation and fertilization for maximum efficiency and profitability.
This project showcases how data-driven decision-making can transform agriculture, making it more efficient, sustainable, and profitable for farmers and stakeholders alike.
