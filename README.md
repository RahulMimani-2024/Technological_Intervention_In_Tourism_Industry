# Technological_Intervention_In_Tourism_Industry 
This project is all about the technological interventions that are required in the tourism industry I have taken the very useful application of AI for the forecasting of foreign tourist arrival in india using the [dataset](https://www.statista.com/statistics/305501/number-of-international-tourist-arrivals-in-india/) which has the monthly tourist arrival in India.
I have created three files :
1. [LSTM](https://colab.research.google.com/drive/1yTI0tZ9pxBtIC9-tQXQUD3SMjFvPspIy#scrollTo=PxVbLiIgCtAk) : In this file I have implemented the LSTM model on the dataset , Firstly I created the dataframe using pandas library in pyhton then splittin it in to the testing and training dataset then created some helpers functions for the visulaization then trained the model after importing it from keras library then using the trained model I predicted the foreign tourist arrival for the next 24 months.
2. [ARIMA](https://colab.research.google.com/drive/1iwzLxO7JQ65gQG3TMmirT_kfo9s1LOZz#scrollTo=8wMr1dsAX0Y4) : In this file I have  implemented the ARIMA model on the dataeset and after training and testing I have used it to predict for the next 24 months
3. [XGBoost](https://colab.research.google.com/drive/1UoLomvYC6l2Wd7Mpu7vdcT1L8yJ7w4Ib#scrollTo=1624iRrKfEXi) : In this file I have implemented the XGBoost gradeint boosting model on the dataset and trained over the training dataset and used the model the predict for the next 24 months.

RESULTS: 
I have caluclated the RMSE of all the three models and I got to know that LSTM outperforms the other two in terms of RMSE.

Future works : 
We can use google search query data to predict the recovery time period of the tourism industry due to pandemic using the same models.

How to run the colab notebooks? 
First of all open the notebook then press on connect and then upload the files attached below after downloading it and run all the cell 
Open [this](https://docs.google.com/spreadsheets/d/15FDCd92FEXP_fpKZuHuUx2XFH6vSBEN6SLhIfEwA5yo/edit?usp=sharing) then download and upload it to the notebook then run all after connecting.
