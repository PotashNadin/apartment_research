Были предоставлены исторические данные: технические характеристики, комплектации и цены автомобилей.
**Цель проекта:**
Построить модель для определения стоимости автомобиля.

Условия от заказчика:
- качество предсказания;
- скорость предсказания;
- время обучения.

В данном проекте была проведена очистка данных, отбор признаков для предсказаний. А так же использовался метод кодирования OHE для LinearRegression и DummyRegressor .
А так же, в данном проекте я впервые использовала библиотеки catboost и lightgbm.
**Библиотеки:**
- pandas
- numpy
- sklearn.model_selection(train_test_split, GridSearchCV)
- sklearn.linear_model(LinearRegression)
- sklearn.dummy(DummyRegressor)
- catboost(CatBoostRegressor, cv, Pool)
- sklearn.tree(DecisionTreeRegressor)
- sklearn.metrics(mean_squared_error,make_scorer)
- lightgbm
- time
- seaborn
