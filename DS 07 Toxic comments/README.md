# Выявление токсичных комментариев

[ipynb](https://github.com/mvs834/Yandex.Practicum-RUS/blob/346d5c78d45f2053aea598555d54ae9550e64705/Car%20Price%20Prediction/Car_Price_Prediction.ipynb)

## Описание проекта

Необходимо искать токсичные комментарии на основе набора данных с разметкой токсичности.


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

Текст загружен, в предобработке не нуждался. Подготовка данных заключалась в очистке от знаков препнания, цифр, символов и пр. кроме букв и приведении к строчным буквам. Лемматизация проводилась двумя способами NLTK (более быстрый) и Spacy (более долгий). Для обучения текстовые данные векторизовались методом TF-IDF. Обучение происходило посредством логистической регрессии и деревянных моделей. Логистическая регрессия показала наилучший результат. Лемматизация оказалась лучше методом Spacy.

В качестве дальнейших шагов по улучшению метрики можно выполнить токенизацию, обучение с градиентным бустингом и векторизацию нейронной сеткой BERT.
