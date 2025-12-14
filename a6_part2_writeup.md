# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Bedrooms
2. Bathrooms
3. Age
4. Least Important: SquareFeet

**Explanation:**
By looking at the coefficients for each feature, I was able to decide which was most important and which was least. The larger the coefficient, the more important it is. Bedrooms had the largest coefficient, meaning that it was the most important.



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:** Age. The coefficient was around -950, meaning that for every year the house gets older, the price of the house decreases by $950. 


**Feature 2:** SquareFeet. the coefficient was around 120, meaning htat for each extra squarefoot that there is, the price of the house increases by around $120.


---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:** My R² score was 0.9936. This tell me that my model is very good at predicting house prices. It also tells me that these features are very important for predicting the price of a house. Yes, there is still room for improvement as R² is not 1, but adding additional feautres will most likely not affect my model by much. 




---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:** Neighborhood 


**Why it would help:** I think that house prices fluctuate based on where a house is located. I think that if a house is located in a neighborhood where there is a very low crime rate and has lots of amenities near it, it would be valued higher than a house that isn't.


**Feature 2:** Parking availability


**Why it would help:** I think that this feature would slightly improve my model's predictions. I think that a house with a 1-2 car garage, or with a residential parking permit would cost more because it is more desireable. Not being able to find parking quickly could affect the price of a house.


---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:** No, I would not trust this model to predict the price of a house with those features. I wouldn't trust it because the features of that house are outside of the range of my training data. My training data only had up to 5 bedrooms, 3 bathrooms, and 2500 square feet. This means that my prediction could be way off. 


