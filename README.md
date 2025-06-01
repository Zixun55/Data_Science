# Data_Science_Term_Project
碩一資料科學期末專案

## Dataset:
>https://www.kaggle.com/discussions/accomplishments/509324

## Midterm report link:
>https://www.canva.com/design/DAGkTA9Yx9I/J4S874pXdDDyAlquyLnkoQ/edit

## 區分男女預測各科目結果
### 男生預測結果
| 科目        | XGBoost | Random Forest Regression(RFR) | Logistic Regression (LR) |
| --------- | ------- | ------------------ | ------------------------ |
| Math      |MSE: 131.31<br>MAE: 8.95<br>R² 分數: 0.2926<br>RMSE: 11.46|MSE: 149.58<br>MAE: 9.49<br>R² 分數: 0.1942<br>RMSE: 12.23|MSE: 140.12<br>MAE: 9.28<br>R² 分數: 0.2452<br>RMSE: 11.84|
| History   |MSE: 149.23<br>MAE: 10.36<br>R² 分數: 0.1240<br>RMSE: 12.22|MSE: 189.28<br>MAE: 11.25<br>R² 分數: -0.1111<br>RMSE: 13.76|MSE: 146.86<br>MAE: 10.27<br>R² 分數: 0.1379<br>RMSE: 12.12|
| Physics   |MSE: 149.11<br>MAE: 10.48<br>R² 分數: 0.0983<br>RMSE: 12.21|MSE: 185.70<br>MAE: 11.31<br>R² 分數: -0.1230<br>RMSE: 13.63|MSE: 149.33<br>MAE: 10.47<br>R² 分數: 0.0969<br>RMSE: 12.22|
| Chemistry |MSE: 149.42<br>MAE: 10.47<br>R² 分數: 0.0897<br>RMSE: 12.22|MSE: 189.21<br>MAE: 11.34<br>R² 分數: -0.1526<br>RMSE: 13.76|MSE: 152.52<br>MAE: 10.63<br>R² 分數: 0.0709<br>RMSE: 12.35|
| Biology   |MSE: 173.36<br>MAE: 10.45<br>R² 分數: 0.1752<br>RMSE: 13.17|MSE: 197.52<br>MAE: 11.17<br>R² 分數: 0.0602<br>RMSE: 14.05|MSE: 168.83<br>MAE: 10.54<br>R² 分數: 0.1967<br>RMSE: 12.99|
| English   |MSE: 139.86<br>MAE: 9.99<br>R² 分數: 0.1271<br>RMSE: 11.83|MSE: 157.08<br>MAE: 10.28<br>R² 分數: 0.0197<br>RMSE: 12.53|MSE: 137.76<br>MAE: 9.74<br>R² 分數: 0.1403<br>RMSE: 11.74|
| Geography |MSE: 134.35<br>MAE: 9.94<br>R² 分數: 0.0629<br>RMSE: 11.59|MSE: 165.38<br>MAE: 10.76<br>R² 分數: -0.1535<br>RMSE: 12.86|MSE: 135.27<br>MAE: 9.96<br>R² 分數: 0.0565<br>RMSE: 11.63|

### 女生預測結果
| 科目        | XGBoost | Random Forest Regression(RFR) | Logistic Regression (LR) |
| --------- | ------- | ------------------ | ------------------------ |
| Math      |MSE: 137.74<br>MAE: 9.27<br>R² 分數: 0.3145<br>RMSE: 11.74|MSE: 185.17<br>MAE: 10.51<br>R² 分數: 0.0784<br>RMSE: 13.61|MSE: 132.84<br>MAE: 9.05<br>R² 分數: 0.3389<br>RMSE: 11.53|
| History   |MSE: 139.75<br>MAE: 10.15<br>R² 分數: 0.1288<br>RMSE: 11.82|MSE: 193.37<br>MAE: 11.40<br>R² 分數: -0.2055<br>RMSE: 13.91|MSE: 153.15<br>MAE: 10.68<br>R² 分數: 0.0453<br>RMSE: 12.38|
| Physics   |MSE: 127.69<br>MAE: 9.58<br>R² 分數: 0.1186<br>RMSE: 11.30|MSE: 166.56<br>MAE: 10.27<br>R² 分數: -0.1496<br>RMSE: 12.91|MSE: 129.34<br>MAE: 9.70<br>R² 分數: 0.1073<br>RMSE: 11.37|
| Chemistry |MSE: 152.63<br>MAE: 10.33<br>R² 分數: -0.0806<br>RMSE: 12.35|MSE: 183.91<br>MAE: 11.20<br>R² 分數: -0.3020<br>RMSE: 13.56|MSE: 143.95<br>MAE: 10.24<br>R² 分數: -0.0192<br>RMSE: 12.00|
| Biology   |MSE: 171.35<br>MAE: 11.05<br>R² 分數: 0.1861<br>RMSE: 13.09|MSE: 167.83<br>MAE: 10.96<br>R² 分數: 0.2028<br>RMSE: 12.96|MSE: 208.66<br>MAE: 11.58<br>R² 分數: 0.0089<br>RMSE: 14.44|
| English   |MSE: 128.53<br>MAE: 9.30<br>R² 分數: 0.1085<br>RMSE: 11.34|MSE: 151.19<br>MAE: 9.88<br>R² 分數: -0.0487<br>RMSE: 12.30|MSE: 130.97<br>MAE: 9.50<br>R² 分數: 0.0916<br>RMSE: 11.44|
| Geography |MSE: 117.27<br>MAE: 9.18<br>R² 分數: 0.0671<br>RMSE: 10.83|MSE: 149.56<br>MAE: 9.90<br>R² 分數: -0.1897<br>RMSE: 12.23|MSE: 118.06<br>MAE: 9.06<br>R² 分數: 0.0608<br>RMSE: 10.87|
