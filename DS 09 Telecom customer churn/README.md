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

## Ход выполнения проекта
### Загрузка и предобработка данных
- названия колонок приведены к нижнему регистру
- пропуски в данных отсутствуют
- типы данных приведены к соответствующим
- исследованы распределения признаков
- созданы новые признаки

### Выбор признаков
- исследованы корреляции признаков

### Исследовательский анализ данных
- ушедшие клиенты имели большие расходы на ежемесячную оплату услуг и не имели дополнительных услуг

### Подготовка данных к обучению
- данные разбиты на выборки
- категориальные признаки закодированы
- количественные признаки масштабированы
- выбраны значимые признаки на основе модели логистической регрессии и модели случайного леса

### Обучение моделей
- обучены модели логистической регрессии, дерева решений, случайного леса, градиентного бустинга с учётом несбалансированности классов LGBM, XGBoost, CatBoost
- выбрана модель LGBM с наилучшим качеством

### Проверка модели на тестовой выборке
- на тестовой выборке получена ROC-AUC 0,89

## Вывод

Была проведена предобработка данных, исследовательская работа по выявлению значимости признаков, создание новых признаков и обучению и выбору модели для прогноза оттока клиентов. Выбрана модель lightgbm, показавшая результат ROC-AUC 0,89.
