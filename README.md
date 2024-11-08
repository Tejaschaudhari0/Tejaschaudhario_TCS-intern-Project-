# TCS_intern-Time Series Forecasting System Project 

The project aims to design and implement a robust Forecasting System that accurately predicts product demand using historical data analysis. By leveraging advanced forecasting models, it provides reliable insights into demand patterns, supporting strategic decision-making, optimizing inventory management, and enhancing operational efficiency in a dynamic business environment.


## Dataset Link :-
- <a href="https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data">Dataset</a>


For this project, the dataset was sourced from the Kaggle Store Item Demand Forecasting Challenge, comprising 913,000 rows organized into four crucial columns—Date, Store, Item, and Sales. This dataset represents a comprehensive repository of historical sales data. The dataset is described as follows :

- Date: Sales date without holiday effects or store closures.
-	Store: Store ID, providing a unique identifier for each store.
-	Item: Product ID, offering a distinct identification number for each product.
-	Sales: Quantity of products sold, indicating the number of products sold from a specific store on a specific date.



## Google Colab Notebook File Link :-

<a href= "https://colab.research.google.com/drive/1LdB4Im8DENt4ceQNd_ycvmHWrvuWFEOh?usp=sharing">Colab Notebook File</a>

NOTE : Please wait, the file may take up to 5 seconds to load.



## Data Analysis Summary :-

- After cleaning the data, exploratory data analysis (EDA) was conducted on historical sales data to identify trends, patterns, and seasonality. 
- Key steps included calculating descriptive statistics, performing correlation analysis to understand relationships with external factors, and decomposing the time series to reveal trend and seasonality.
- Data visualization techniques such as time series, seasonal, and distribution plots helped uncover patterns, anomalies, and sales distribution characteristics.
  
These insights provided essential guidance for selecting the appropriate forecasting models.



![image](https://github.com/user-attachments/assets/cbbd86e1-4ac8-40cd-8012-1fdab8af5f96)




## Splitting the Data :-

The dataset was divided into 80% for training and 20% for testing, ensuring an effective evaluation of the model’s efficiency and accuracy.



## Modelling :-

Three forecasting models—SARIMAX, Holt-Winters Exponential Smoothing (HWES), and Prophet—were implemented to predict future demand.

- SARIMAX :  Selected for its ability to capture seasonality and trend.
- HWES :  Chosen for managing seasonality, trend, and emphasizing recent observations.
- Prophet :  Used for its flexibility in handling seasonality, holidays, and missing data, with automatic parameter optimization. Each model underwent parameter tuning for improved accuracy.
  


![image](https://github.com/user-attachments/assets/7fd902c0-aa6e-4206-a14c-4849bdd69627)



## Project Insights :-

The project highlights the importance of selecting the right forecasting model for demand prediction. The SARIMAX model proved to be a reliable choice, offering robust predictions. The use of evaluation metrics ensured model accuracy, and the project's approach provides a solid foundation for future forecasting efforts. Additionally, integrating Deep Learning techniques could enhance model performance, leading to more precise demand forecasts and better inventory management.


## Conclusion :-

The SARIMAX model was selected as the top-performing forecasting model due to its superior accuracy in predicting demand across diverse stores. Evaluated using MAE, MSE, and RMSE, SARIMAX consistently outperformed HWES and Prophet. The project successfully developed an effective forecasting system, with a well-structured methodology encompassing data cleaning, analysis, and model fine-tuning. The exploration of Deep Learning (DL) techniques offers exciting potential for further improving forecasting accuracy.



