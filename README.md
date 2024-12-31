# Car-price-prediction
Car price prediction using regression
### <font color='Green'> <u>Problem Description </u>:</font>
A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

1. **Which variables are significant in predicting the price of a car.**
   - Identify the key factors that influence car pricing, such as engine size, mileage, brand, etc.
   
2. **How well those variables describe the price of a car.**
   - Determine the strength and relevance of these factors in accurately predicting the car's price.
  
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.
#### <font color='Green'><u> Business Goal</u></font>
You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to
#### <font color='Red'>1. <u>Understand Problem Statement</u></font>
1. **Clarify the business goal: Predict car prices using independent variables and understand which factors significantly impact the price.The target variable (also known as the dependent variable or response variable) is the variable that you want to predict.Here it is the price**
2. **Emphasize the importance of understanding the pricing dynamics to aid the company's strategic decisions in a new market.**
   
#### <font color='red'>8.Evaluation of models</red>
1.**<u>Random Forest Regressor:</u>**
Best performance with the lowest MSE (1,960,059.2142), lowest RMSE (1,400.021), and highest R² score (0.8834). This indicates that the model is         capturing most of the variability in car prices and providing accurate predictions.

2. **<u>Gradient Boosting Regressor:</u>**
Close second with slightly higher error metrics than Random Forest, but still a strong model for predicting car prices.

3. **<u>Linear Regression:</u>**
Performed reasonably well but was outperformed by the ensemble methods. MSE (3,236,009.8200) and R² score (0.8075) indicate that while it captures some of the variability, it’s not as robust as the ensemble methods.

4. **<u>Decision Tree Regressor:</u>**
This model did not perform as well as the Random Forest or Gradient Boosting Regressors. Its MSE and RMSE are higher, and the R² score is lower, indicating that it is less accurate in predicting car prices.MSE: 4,485,063.9399,RMSE: 2,117.797,R² Score: 0.7332

5. **<u>Support Vector Regressor (SVR):</u>**
Worst performance with extremely high error metrics and a negative R² score, indicating that the model fails to capture the relationship between features and car prices effectively.

#### <font color='Red'> Analysis </font>
><u><b>Best-Performing Model</u></b>: The Random Forest Regressor remains the best-performing model, with the lowest error metrics and the highest R² score. It captures the relationships in the data more effectively than the other models.

#### <font color='red'><u>Conclusion</u></font>
The results indicate that ensemble methods, particularly the Random Forest Regressor, provide the most reliable predictions for car prices in this context. These insights can be leveraged by the Chinese automobile company to fine-tune their car designs and pricing strategies for successful entry into the U.S. market.

#### Disclaimer
This project is provided for informational and educational purposes only. While every effort has been made to ensure the accuracy and reliability of the information contained in this repository, it is provided "as is" without warranty of any kind.

The contributors to this project shall not be held responsible for any damage, issues, or losses that arise from using the code, resources, or information contained herein. Users are encouraged to review, test, and adapt the content according to their needs and ensure it complies with applicable laws and regulations.

If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.
