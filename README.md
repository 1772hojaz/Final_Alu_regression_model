## **Project Overview**
This project is a sales prediction system built using a trained regression model. It predicts sales for retail products based on various features such as outlet size, location type, and product information. The project includes:
- A trained regression model using Scikit-learn.
- A FastAPI-based backend for API services.
- A Flutter frontend for user interaction.

Model1 R-squared: 0.5340612546359426
Model2 R-squared: 0.2544934386954585
model3 R-squared: 0.2544934386954585


## **Features**
The system predicts sales based on the following input features:
1. **Item_MRP**: Maximum retail price of the item (float).
2. **Outlet_Size**: Size of the outlet (`small`, `medium`, `large`).
3. **Outlet_Location_Type**: Location type of the outlet (`Tier1`, `Tier2`, `Tier3`).
4. **Outlet_Type**: Type of the outlet (`0`, `1`, `2`, `3`).
5. **New_Item_Type**: Type of item (`Food`, `Drinks`, `Non-Consumable`).
6. **Outlet_Years**: Number of years since the outlet's establishment (integer).


**Data set**

Data source https://www.kaggle.com/datasets/devashish0507/big-mart-sales-prediction/data



**My Mission**
To increase the availability of safety tools among informal sector workers, reducing the cost and maximising the durability of the safety tools thus, making workplaces safer.


**Video Recording**
https://www.youtube.com/watch?v=rcxsdtxKjvc 

**Flutter app repo**
https://github.com/1772hojaz/project.git

**Frontend setup**
1. clone the flutter app repository:
   ```bash
       git clone [git@github.com:1772hojaz/project.git](https://github.com/1772hojaz/project.git)

3. Install Dependencies:
   ```bash
       cd project
       flutter pub get
3.Run app: 
    ```bash
        flutter run

**Back-end API REPO**
**Back-End SetUp**
1. clone:
   ```bash
       git clone https://github.com/1772hojaz/Regression_model.git
2.Install Dependencies:
     ```bash
       cd backend
       pip install -r requirements.txt
3. run api:
    ```bash
        uvicorn main:app --reload


 
