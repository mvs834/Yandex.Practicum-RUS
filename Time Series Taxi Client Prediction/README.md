# Временные ряды. Прогноз количества клиентов

[ipynb](https://github.com/mvs834/Yandex.Practicum-RUS/blob/2cf5878f435784bf943c845d927df48d96293d13/Time%20Series%20Taxi%20Client%20Prediction/Time_Series_Taxi_Clients_Prediction_RMSE_6.9.ipynb)

## Описание проекта

Необходимо проанализировать исторические данные о заказах такси в аэропортах и на этой основе спрогнозировать количество заказов такси на следующий час



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- matplotlib.**pyplot**
- **seaborn**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.pipeline.**make_pipeline**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- **lightgbm**
- **xgboost**
- catboost.**CatBoostRegressor**


## Вывод

Была проведена предобработка данных (очистка от выбросов, проверка наличия пропусков и дубликатов, проверка моностонности, перемасштабирование), исследовательская работа по анализу сезонности, и обучение и выбор модели для прогноза количества клиентов такси в следующем часу. Наименьшую ошибку имеет модель дерева решений с параметром max_depth = 4. При таком гиперпараметре на тестовой выборке метрика RMSE составляет 6.9
