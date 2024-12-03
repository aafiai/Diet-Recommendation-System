# Diet-Recommendation-System
The code implements a personalized diet recommendation system that calculates BMI, BMR, and TDEE based on user inputs like weight, height, age, and activity level. It suggests meals from a dataset based on calorie targets, dietary preferences, and weight goals. It also predicts bioimpedance using a RandomForestRegressor model.


The code offers several key features and functionalities for personalized diet planning and bioimpedance prediction:

1. BMI Calculation & Categorization: It calculates Body Mass Index (BMI) and categorizes it into four ranges—Underweight, Normal weight, Overweight, and Obese—based on user inputs of weight and height.

2. TDEE Calculation: It computes the Total Daily Energy Expenditure (TDEE) based on the Basal Metabolic Rate (BMR) and activity level, helping users understand their calorie needs.

3. Calorie Requirements for Weight Loss: The system adjusts calorie requirements for different weight loss plans (e.g., "Maintain weight," "Lose Mild Weight," etc.), providing users with specific calorie targets based on their goals.

4. Meal Recommendations: It offers breakfast, lunch, and dinner recommendations based on dietary preferences (veg/non-veg) and selected calorie targets, selecting food items from a dataset and ensuring that the total calories do not exceed the set target.

5. Bioimpedance Prediction: It uses a RandomForestRegressor model to predict bioimpedance based on a user's age, weight, height, and gender, providing insights into their body composition.

6. Data Preprocessing: The system handles preprocessing of data for meal suggestions and bioimpedance prediction, including cleaning and normalization of input datasets.

This functionality allows users to receive personalized meal plans and health insights tailored to their physical metrics and fitness goals.
