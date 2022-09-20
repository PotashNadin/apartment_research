В данном проекте рассмотрим данные компании сотового оператора. Это моя первая практическая работа с моделями машинного обучения. 

**Цель проекта:** проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В данном проекте я провела предобработку данных, обучила три модели машинного обучения на тренировочных данных, проверила их работу на валидационной выборке. 
Итоговые предсказания провела на тестовой выборке. В данной работе я использовала следующие **библиотеки:**
- pandas,
- seaborn
- sklearn.model_selection(train_test_split, GridSearchCV)
- sklearn.ensemble(RandomForestClassifier)
- sklearn.tree(DecisionTreeClassifier)
- sklearn.linear_model(LogisticRegression)
- sklearn.metrics(accuracy_score, recall_score, precision_score)
- sklearn.dummy(DummyClassifier)
