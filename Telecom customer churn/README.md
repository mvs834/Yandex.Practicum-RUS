# Прогноз оттока клиентов

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