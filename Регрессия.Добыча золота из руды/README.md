Компания предоставила данные, содержащие информацию об этапах отчистки руды и количества концентрации золота в финальных этапах.

**Цель проекта:**
Предсказать коэффициент восстановления золота из золотосодержащей руды.

В данном проекте мною была проведена предобработка данных и исследовательский анализ данных.
На основе полученной информации я определила актуальные признаки для модели(исключив те, которые могли привести к переобучению модели) и построила саму модель.
Оценку предсказаний производила с помощью функции sMAPE.

**Библиотеки:**
- pandas
- numpy
- matplotlib.pyplot
- sklearn.metrics(mean_absolute_error, mean_squared_error, make_scorer)
- sklearn.model_selection(GridSearchCV, cross_val_score)
- sklearn.linear_model(LinearRegression)
- sklearn.tree import(DecisionTreeRegressor)
- sklearn.ensemble(RandomForestRegressor)
- sklearn.dummy(DummyRegressor)
