Предоставлен датасет комментариев на английском языке. 

**Цель проекта:**
Построить модель классификации комментариев на позитивные и негативные.

Проведена работа по очистке тектса от знаков препинания, лемматизация и токенизация. Сформировав матрицы признаков, данные были поданы модели для обучения.
Оценка качества модели проводилась с помощью метрики f1_score.

**Библиотеки:**

- pandas
- re
- nltk
- nltk.corpus(wordnet)
- nltk.corpus(stopwords as nltk_stopwords)
- nltk(word_tokenize)
- nltk.stem(WordNetLemmatizer)
- sklearn.feature_extraction.text(CountVectorizer,TfidfVectorizer)
- sklearn.model_selection(train_test_split)
- sklearn.linear_model(LogisticRegression)
- catboost(CatBoostClassifier, Pool)
- sklearn.metrics(f1_score)
- sklearn.tree(DecisionTreeClassifier)
