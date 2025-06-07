# Data_Science_Term_Project
碩一資料科學期末專案

## Dataset:
>https://www.kaggle.com/discussions/accomplishments/509324

## Midterm report link:
>https://www.canva.com/design/DAGkTA9Yx9I/J4S874pXdDDyAlquyLnkoQ/edit

## 區分男女預測各科目結果
### 男生預測結果
| 科目        | XGBoost | Random Forest Regression(RFR) | Linear Regression (LR) |
| --------- | ------- | ------------------ | ------------------------ |
| Math      |MSE: 80.84<br>MAE: 7.24<br>R² 分數: 0.1845<br>RMSE: 8.99|MSE: 91.19<br>MAE: 7.57<br>R² 分數: 0.0801<br>RMSE: 9.55|MSE: 79.42<br>MAE: 7.25<br>R² 分數: 0.1988<br>RMSE: 8.91|
| History   |MSE: 119.62<br>MAE: 9.16<br>R² 分數: 0.1139<br>RMSE: 10.94|MSE: 155.92<br>MAE: 10.12<br>R² 分數: -0.1549<br>RMSE: 12.49|MSE: 122.70<br>MAE: 9.22<br>R² 分數: 0.0912<br>RMSE: 11.08|
| Physics   |MSE: 114.96<br>MAE: 8.97<br>R² 分數: 0.1857<br>RMSE: 10.72|MSE: 143.03<br>MAE: 9.67<br>R² 分數: -0.0131<br>RMSE: 11.96|MSE: 121.43<br>MAE: 9.12<br>R² 分數: 0.1399<br>RMSE: 11.02|
| Chemistry |MSE: 152.99<br>MAE: 10.75<br>R² 分數: 0.0648<br>RMSE: 12.37|MSE: 183.15<br>MAE: 11.19<br>R² 分數: -0.1196<br>RMSE: 13.53|MSE: 160.80<br>MAE: 11.15<br>R² 分數: 0.0170<br>RMSE: 12.68|
| Biology   |MSE: 164.92<br>MAE: 11.22<br>R² 分數: 0.1348<br>RMSE: 12.84|MSE: 199.03<br>MAE: 11.67<br>R² 分數: -0.0441<br>RMSE: 14.11|MSE: 171.49<br>MAE: 11.44<br>R² 分數: 0.1004<br>RMSE: 13.10|
| English   |MSE: 116.17<br>MAE: 8.76<br>R² 分數: 0.1334<br>RMSE: 10.78|MSE: 134.40<br>MAE: 9.36<br>R² 分數: -0.0026<br>RMSE: 11.59|MSE: 118.47<br>MAE: 8.92<br>R² 分數: 0.1162<br>RMSE: 10.88|
| Geography |MSE: 131.32<br>MAE: 9.57<br>R² 分數: 0.0518<br>RMSE: 11.46|MSE: 160.83<br>MAE: 10.72<br>R² 分數: -0.1613<br>RMSE: 12.68|MSE: 133.23<br>MAE: 9.68<br>R² 分數: 0.0380<br>RMSE: 11.54|

### 女生預測結果
| 科目        | XGBoost | Random Forest Regression(RFR) | Linear Regression (LR) |
| --------- | ------- | ------------------ | ------------------------ |
| Math      |MSE: 106.51<br>MAE: 8.10<br>R² 分數: 0.2198<br>RMSE: 10.32|MSE: 123.13<br>MAE: 8.44<br>R² 分數: 0.0980<br>RMSE: 11.10|MSE: 98.60<br>MAE: 7.96<br>R² 分數: 0.2777<br>RMSE: 9.93|
| History   |MSE: 143.45<br>MAE: 10.10<br>R² 分數: 0.0360<br>RMSE: 11.98|MSE: 191.17<br>MAE: 11.24<br>R² 分數: -0.2846<br>RMSE: 13.83|MSE: 147.82<br>MAE: 10.36<br>R² 分數: 0.0066<br>RMSE: 12.16|
| Physics   |MSE: 137.69<br>MAE: 9.91<br>R² 分數: 0.0262<br>RMSE: 11.73|MSE: 185.27<br>MAE: 11.08<br>R² 分數: -0.3103<br>RMSE: 13.61|MSE: 144.09<br>MAE: 10.19<br>R² 分數: -0.0191<br>RMSE: 12.00|
| Chemistry |MSE: 152.71<br>MAE: 10.63<br>R² 分數: 0.0578<br>RMSE: 12.36|MSE: 175.04<br>MAE: 10.90<br>R² 分數: -0.0799<br>RMSE: 13.23|MSE: 154.38<br>MAE: 10.70<br>R² 分數: 0.0475<br>RMSE: 12.43|
| Biology   |MSE: 140.29<br>MAE: 10.16<br>R² 分數: 0.1266<br>RMSE: 11.84|MSE: 196.44<br>MAE: 11.65<br>R² 分數: -0.2230<br>RMSE: 14.02|MSE: 139.43<br>MAE: 10.03<br>R² 分數: 0.1320<br>RMSE: 11.81|
| English   |MSE: 132.48<br>MAE: 9.72<br>R² 分數: 0.1171<br>RMSE: 11.51|MSE: 158.02<br>MAE: 10.19<br>R² 分數: -0.0531<br>RMSE: 12.57|MSE: 142.05<br>MAE: 10.01<br>R² 分數: 0.0533<br>RMSE: 11.92|
| Geography |MSE: 117.79<br>MAE: 9.14<br>R² 分數: 0.0133<br>RMSE: 10.85|MSE: 158.81<br>MAE: 10.35<br>R² 分數: -0.3303<br>RMSE: 12.60|MSE: 121.18<br>MAE: 9.13<br>R² 分數: -0.0151<br>RMSE: 11.01|
