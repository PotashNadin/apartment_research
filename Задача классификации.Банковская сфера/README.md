В рамках данного проекта были предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

**Цель проекта:** 
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.

Для оценки качества прогноза в данном проекте использовалась метрика F1 и построена кривая ошибок ROC-AUC. Была протестирована работа трех моделей машинного обучения и выбрана наилучшая.

**Библиотеки**, которые были использованы в данном проекте:
- pandas
- seaborn
- matplotlib.pyplot as plt
- sklearn.model_selection(train_test_split)
- sklearn.ensemble(RandomForestClassifier)
- sklearn.tree (DecisionTreeClassifier)
- sklearn.linear_model(LogisticRegression)
- sklearn.metrics(f1_score, roc_curve, roc_auc_score)
- sklearn.utils(shuffle)

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)
