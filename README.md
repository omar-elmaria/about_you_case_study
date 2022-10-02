![About You Background Image](https://user-images.githubusercontent.com/98691360/190907068-6ba4a1a8-67b6-4db6-8b9c-a6d0779027e8.jpg)

# About You Case Study
This repo contains a full analysis of the sales, promo, and pricing trends of fashion products sold by the European E-commerce company "About You". "About You" is a 
German fashion online retailer based in Hamburg with an **annual revenue just shy of a billion** and operations in 24 countries. The insights of this case study are neatly
presented in this [slide deck](https://docs.google.com/presentation/d/1lUUm42_86o2Zgdu4VqKDmmXWKSfQuvIHZgyQ36Mt5wc/edit?usp=sharing)

# 1. The Objective of the Project
This was an open-ended project where the goal was to analyze this [dataset](https://drive.google.com/file/d/1-4hp4YB6waePDE9IDIKu_gy7i6_rQ12m/view?usp=sharing) and 
provide an exploratory data analysis EDA using **Python**. Some of the questions that I attempted to answer were:
- What is the **structure of the dataset**? What does the data in convey and what is the **granularity of the table**?
- What are some **interesting statistics** that could be reported about the dataset?
- How do the **top five product groups** fare against each other in terms of **price points, sales, and promo trends**?
- Could we fit an **ARIMA** model to predict the order volume throughout the year?

# 2. General Statistics About the Dataset
![image](https://user-images.githubusercontent.com/98691360/190910157-ed1a2c70-94b4-44d1-b3c1-1f2a49bf30ab.png)
![image](https://user-images.githubusercontent.com/98691360/190910243-095f3b5c-7ffd-4a53-9d4a-289713b7ffa3.png)

# 3. Top Charts Created from the Data
## 3.1 Price Points by Product Group and Season
![image](https://user-images.githubusercontent.com/98691360/190910527-1e96f726-baad-4acb-adb3-641e6f498ea7.png)

## 3.2 The Number of Orders and Inventory Trends Showing the Seasonal Behavior
![image](https://user-images.githubusercontent.com/98691360/190910684-be43793c-076f-4768-b3a4-6c92f83763a1.png)

## 3.3 Heatmaps Showing the Peak Sales Periods Per Product Group
![image](https://user-images.githubusercontent.com/98691360/190910724-4cbc503f-8225-46ed-a015-01469e687f23.png)

## 3.4 Fitting the ARIMA Model to the Data
![image](https://user-images.githubusercontent.com/98691360/190910781-441ae48f-e782-4545-9681-67b334fc9591.png)

# 2. Usability and Reproducability
- **Clone the repo** using this command in your terminal
```git clone https://github.com/omar-elmaria/about_you_case_study.git```
- **Create a virtual environment** by running this command ```python -m venv venv_about_you_challenge```
- **Activate the virtual environment** by typing this ```source venv_about_you_challenge/bin/activate``` if you are on Mac/Linux or ```source venv_about_you_challenge/Scripts/activate``` if you are on Windows. You might need to replace the forwardslashes with a backslash if you are on Windows
- **Double-check that you are using the correct Python path** by typing ```which python``` and clicking enter (```which python3 on Mac/Linux```). It should point to the Python executable in the virtual environment you just created
- ```Ctrl-Shift-P``` to **view the command palette in VSCode** --> ```Python: Select Interpreter``` --> **Browse to the Python executable in your virtual environment** so that the Jupyter notebook uses the correct Python interpreter
- Run this command in the terminal to **install the required dependencies** ```pip install -r requirements.txt```
- You will likely need to change the path to the dataset stored in the **.parquet file** in step 1
- **Start executing each cell in the Jupyter notebook** and the code will run fine
