Restaurant Recommendation Engine for Akeed
Project Objective
The goal of this project is to build a recommendation engine to predict which restaurants customers are most likely to order from based on customer location, restaurant information, and customer order history. 
This solution will enable Akeed, an app-based food delivery service in Oman, to provide personalized restaurant recommendations for their customers, enhancing the overall user experience.

Dataset
The dataset used for this project includes various features related to customers, restaurants, and order history. 
Key steps in data preparation include handling missing values, encoding categorical variables, and dropping non-numeric and irrelevant columns.

Data Preprocessing
The data preprocessing steps include:

Handling missing values by dropping rows with missing data.
Encoding categorical variables using LabelEncoder.
Dropping non-numeric and irrelevant columns: vendor_category_en, vendor_tag_name, device_type, payment_mode, gender.

Model Training and Evaluation
Decision Tree Regressor
A Decision Tree Regressor is used to predict the restaurant (vendor_id) a customer is likely to order from. 
The model is evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics.

Hyperparameter Tuning
GridSearchCV is used for hyperparameter tuning to optimize model performance.

Binary Classification
For binary classification, the target variable is converted to two classes: "Small Vendor" and "Large Vendor".

Conclusion
The developed models show exceptional performance metrics, indicating a strong foundation for a recommendation engine that can accurately predict customer preferences for restaurants. This will enable Akeed to provide personalized recommendations, enhancing user satisfaction and engagement.

Future Work
Validate the models on new, unseen data.
Explore additional features and model types (e.g., random forests, gradient boosting).
Implement regularization techniques to ensure the models are not overfitting.
Integrate the recommendation engine into the Akeed app for real-time predictions.

Contact
For any questions or feedback, please contact zamokuhlengcobo362@gmail.com.

