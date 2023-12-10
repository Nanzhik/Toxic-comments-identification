# Определение токсичных комментариев

[ipynb]()

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.

## Навыки и инструменты

- **python**
- **pandas**
- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.linear_model.**SGDClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.naive_bayes.**MultinomialNB**

## Вывод

Проведена исследовательская работа по обработке текстов и обучению и выбору модели для определения токсичных комментариев по методу *TF-IDF*. Выбрана линейная регрессия. Даны рекомендации по установке входного фильтра при оставлении комментариев, а также возможные шаги по улучшению результатов.
