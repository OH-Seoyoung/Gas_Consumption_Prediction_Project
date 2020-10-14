# Gas Consumption Prediction Project (20200409)
- Prediction of  Busan city's gas consumption from 2018-06 to 2019-05
- Linear Regression, LSTM models

### First project in data analysis club
- NIMS PLIM industrial problem competition
- This project is maintained by 오서영, [허지혜](https://github.com/jihyeheo), [이수빈](https://github.com/I-SUBIN), [강수연](https://github.com/Kangsooyeon) (Department of Mathematics)  
  
- [[Presentation]](https://github.com/OH-Seoyoung/Gas_Consumption_Prediction_Project/blob/master/Gas_Consumption_Prediction_Project_Presentation.pdf)


## Dataset  
```
[1] BUSAN_gas_consumption dataset, https://icim.nims.re.kr/platform/question/16#summary  
[2] [BUSAN_average_tempurature](https://github.com/OH-Seoyoung/Gas_Consumption_Prediction_Project/blob/master/ta_20200329144537.csv), https://data.kma.go.kr/stcs/grnd/grndTaList.do?pgmNo=70
```

## Results
#### 1. Linear Regression  
RMSE error : 28.55174  
#### 2. Linear Regression with Gradient Descent  
RMSE error : 29.39890  
- gradient descent TOL (tolerance)  
#### 3. LSTM  
RMSE error : 23.38848  
