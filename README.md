# Sales Prediction 
 The Big Mart Sales Practice Problem is an exercise that is part of Coding Dojo: Data Science Bootcamp. The goal of this is to help the retailer understand     the properties of products and outlets that play crucial roles in increasing sales.

**Author**: 
-  Name: Larson Bodden
-  Email: Larsonobodden@gmail.com
-  Phone Number: 917-736-8267

### Business problem:

 Objective:

 - The goal of this exercise is to help the retailer (Big Mart) to understand the properties of products and outlets that play crucial roles in predicting sales for 2023.


Scope:

Our study consists of two parts. The first one is where we developed a visual analysis in order to understand the current situation of the sales, focused on how the visibility index could affect the sales performance.
In Part II, we prepared our data for Machine Learning, evaluating two regression methods to predict the sales for 2023.
Dataset:

The data set can be found here.
In context (as is reported in Part I):
We have three variables that we consider that would affect the sales volume (Variables Type A):
Item_Visibility.
Item_Type.
Item_MRP.
We identified three variables that could affect the sales behavior (Variables Type B):

Outlet_Size.
Outlet_Location_Type.
Outlet_Type.
We are going to work with the variables described above to compare their relationship with Item_Outlet_Sales, our target.

For our Machine Learning model:

Target (y):
Item_Outlet_Sales.
Features (X):
Numerical:
Item_Visibility.
Item_MRP.
Categorical:
Item_Type.
Outlet_Size.
Outlet_Location_Type.
Outlet_Type.

## Results


#### Item Fat Content Vs Item Weight

![Item Fat Content vs Item Weight](https://user-images.githubusercontent.com/107776771/182735938-08c8cd4d-df68-4568-bd29-3960175a056c.png)

> Based on the visualization Low Fat has a higher Item Weight than Regular Fat Content. 

#### Item Fat Content and Item Weight By Item Type

![download](https://user-images.githubusercontent.com/107776771/182736380-edf2dbbe-097a-41ee-8500-66ad40aa45b5.png)

> Based on the visualization Item weight has slightly decreased as the years go on and Item MRP steadly flucates from 1985 to 1997 but dips up and down go into to 2010.

## Model

Our random forest performed the same as the train data. It can predict 100% of our training data.


## Recommendations:

- For Part I:
  - As Section 8.2.1. shows in the notebook, we recommend finishing the code in order to determine how much the visibility index increase per store and product type. That way our recommendation would be more realistic than assuming the index increase 20% in total.
  - After the modification, is important to check the Pareto again in order to keep the focus point displayed throughout the case study.
- For Part II:
  - Append the NumPy Array (predicted values) to the original dataset to compare and evaluate how much the sales would be in 2023.
  - Make another visual analysis in order to manage the new insights.
  - Create a new simulation including the cost of the visibility improvement, where maybe not all product types require the improvement after the append.


## Limitations 

-  Not having access to the data administrator made us infer and play with the data in a way that maybe is not factible.
-  One of the biggest assumptions is how the visibility index works.


## For further information

- For any additional questions, please contact **email**
