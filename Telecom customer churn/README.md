# Прогноз оттока клиентов телекоммуникационной компании

[ipynb](https://github.com/mvs834/Yandex.Practicum-RUS/blob/8e47d9a14f590bd0f375b9f6a1d9b4edb528c687/Telecom%20customer%20churn/Telecom_Customer_Churn_LGBM_0,89.ipynb)

## Описание проекта

Требуется анализировать персональные данные клиентов, их подключённые услуги и расходы, и прогнозировать возможный отток клиентов



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- matplotlib.**pyplot**
- **seaborn**
- sklearn.feature_selection.**SequentialFeatureSelector**
- sklearn.inspection.**permutation_importance**
- sklearn.linear_model.**LogisticRegression**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- **lightgbm**
- **xgboost**
- catboost.**CatBoostClassifier**



## Вывод

Была проведена предобработка данных, исследовательская работа по выявлению значимости признаков, создание новых признаков и обучению и выбору модели для прогноза оттока клиентов. Выбрана модель lightgbm, показавшая результат ROC-AUC 0,89.
