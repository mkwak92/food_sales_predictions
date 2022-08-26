# Food Sales Predictions


# Predicting Sales of Grocery/Supermarket Outlets
## Subtitle describing the analysis 

**Author**: 

### Business problem:
Make predictions about future sales based on provided data about food, item weight, fat content, store size, and other relevant items


### Data:
- Item_Identifier:	Unique product ID
- Item_Weight:	Weight of product
- Item_Fat_Content: Whether the product is low fat or regular
- Item_Visibility:	The percentage of total display area of all products in a store allocated to the particular product
- Item_Type:	The category to which the product belongs
- Item_MRP:	Maximum Retail Price (list price) of the product
- Outlet_Identifier:	Unique store ID
- Outlet_Establishment_Year:	The year in which store was established
- Outlet_Size: The size of the store in terms of ground area covered
- Outlet_Location_Type:	The type of area in which the store is located
- Outlet_Type: Whether the outlet is a grocery store or some sort of supermarket
- Item_Outlet_Sales:	Sales of the product in the particular store. This is the target variable to be predicted.


## Methods
- Load Data
- Data Cleaning (missing values, duplicate values, null values)
- Preprocessing
- Exploratory Vizulations
- Explantatory Vizulations
- Machine Learning
- Preprocessing
- Train/Test Split
- Regression Metrics

## Results

### Here are examples of how to embed images from your sub-folder


#### Outlet Sales vs Unique Store
![OutletSales_Outlet_ID](https://user-images.githubusercontent.com/109184607/186799074-e3101c2d-4273-40e0-933c-8de417fb1cd3.png)


> This shows the Outlet sales vs the specific sale.

#### 
![image](https://user-images.githubusercontent.com/109184607/186799205-2ea7071c-6079-48bf-ac10-ecb417f5235f.png)
- The visual above shows effects of Outlet Size, Outlet Type, and Outlet Location versus sales. 
- The Medium sized outlet scored the highest sales, but there does seem to be much difference the medium size and high size. It makes sense that the small size outlet had the least amount of sales. 
- The data dictionary did not provide any detail on what it means to be a different type of supermarket, but the Supermarket Type3 exceeded well more than any other type of grocery store or supermarket. 
- The Location vs Sales, there does not seem to be much difference in location and their respective sales. Again, the data dictionary does not provide what it means to be in each Tier. 
## Model

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
