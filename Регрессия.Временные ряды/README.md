Предоставлен датасет, содержащий исторические данные о заказах такси в аэропортах.

**Цель проекта:**
спрогнозировать количество заказов такси на следующий час.

В данном проекте ведется работа с временными рядами. Было выполнено ресемплирование по одному часу, проведен анализ данных, отобраны признаки и обучены несколько моделей.
Оценка качества модели проводилась по метрике RMSE.

**Библиотеки:**
- pandas as pd
- statsmodels.tsa.seasonal(seasonal_decompose)
- sklearn.metrics(mean_squared_error,make_scorer)
- sklearn.model_selection(train_test_split, GridSearchCV,TimeSeriesSplit)
- sklearn.linear_model(LinearRegression)
- sklearn.dummy(DummyRegressor)
- sklearn.tree(DecisionTreeRegressor)
- sklearn.ensemble(RandomForestRegressor)
- catboost(CatBoostRegressor)
- matplotlib.pyplot
