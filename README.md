# Food_Sales_Predictions
Predicts future prices of food items

Summary
---
This project predicts the total sales in dollars of a variety of items using a Decision Tree Regressor.

Data Set
---
The data set used for this project is 8523 rows, and 12 columns. Item_Outlet_Sales is the target columns, 10 columns are used as features, and Item_Identifier is dropped.

Summary of the data types:

![image](https://user-images.githubusercontent.com/99829862/161204948-89263179-602f-4287-87f2-cdcd37b3d6a9.png)

Item prices range from $31 to $267, accross 10 store locations in 3 different sizes, and 4 outlet type categories.

 ![image](https://user-images.githubusercontent.com/99829862/161204404-4ac1cd08-8b05-4373-bc74-7186999983c2.png)

 ![image](https://user-images.githubusercontent.com/99829862/161204379-399409d9-64b4-4c66-8e2f-eb6f4fff2101.png)
 
Model
---

The Model is built with a standard 75/25 train test split. The decision tree regressor was fit on the training set using a tree depth of 5. This depth was determined using R2 scores of the test set at various tree depths.

The fitting metrics for the final model as are follows:
  
Training Scores for Decision Tree
-R2: 0.6039 
-MAE: 762.76 
-MSE: 1,172,230.06 
-RMSE: 1,082.70

Test Scores for Decision Tree
-R2: 0.5950 
-MAE: 737.63 
-MSE: 1,117,324.23 
-RMSE: 1,057.04
