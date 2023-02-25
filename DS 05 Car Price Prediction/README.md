# Прогноз рыночной цены автомобиля

[ipynb](https://github.com/mvs834/Yandex.Practicum-RUS/blob/346d5c78d45f2053aea598555d54ae9550e64705/Car%20Price%20Prediction/Car_Price_Prediction.ipynb)

## Описание проекта

Необходимо оценить рыночную стоимость автомобиля на основе исторических данных, включающих технические характеристики, комплектации и цены автомобилей.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- matplotlib.**pyplot**
- **seaborn**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.**pipeline**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- **lightgbm**
- **xgboost**
- catboost.**CatBoostRegressor**





## Вывод

Была проведена предобработка данных (смена формата, обработка пропусков и выбросов), исследовательская работа по определению выбросов, создание новых признаков и обучению и выбору модели для прогноза цены. Выбрана модель catboost, показавшая наименьший результат RMSE 29,1 за достаточно короткое время
