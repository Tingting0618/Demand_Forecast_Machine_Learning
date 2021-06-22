# Hotel Demand Forecast - Machine Learning

## The goal/inspiration

In the project, we are going to forecast hotel occupancy 4 days out (e.g., Today is Monday, and we will be forecasting this Friday's occupancy.)

### Results

Mean Absolute Error (MAE) on a hold-out set = 4.9%. In other words, on average, we are <5% off when forecasting a hotel's occupancy. As a comparison, when there is no model (i.e., directly use last year's occupancy as this year's occupancy on a same weekday), we are on average 8% occupancy points off.

### Methods used

0) Cross-fold validation
1) Same Day Last Year
2) Random Forest
3) Ridge Regression
4) Lasso Regression
5) Multiple Regression
6) Grid Search for hyperparameter tuning

### Technologies used

Python, SQL

### Data source

Historical and forward-looking, property-level hotel demand data is provided by STR SHARE Center. STR is the leading provider of premium global data benchmarking, analytics, and marketplace insights. The STR SHARE Center provides hotel and tourism data to professors for research, student projects, and use in the classroom.

## Learn More

You can learn more in the [Tingting Duan's Project Portfolio](https://tingting0618.github.io).

