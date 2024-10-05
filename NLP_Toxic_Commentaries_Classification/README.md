[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

# Классификация токсичных комментариев. 

## Проблема.
Разработка модели классификации комментариев на позитивные и негативные.<br>
## Решение.
Для классификации токсичных комментариев была использована модель оценки токсичности комментариев _toxic-bert_ и применена логистическая регрессия: _F1_= 0.93. 

<u><b>Внимание! В работе анализируется нецензурная лексика на английском языке.</b></u><br>
[Ссылка на проект.](https://github.com/mrBrain101/Yandex_Practicum_projects/blob/252b54e221a78f82e25ea3cd6ba972843142b394/NLP_Toxic_Commentaries_Classification/Ya_Practicum-NLP_Text_Toxicity_Prediction_distr_RUS.ipynb)

## Этапы:
<li>Исследовательский анализ данных. 
<li>Предобработка данных:<ul>
<li>Фильтрация и лемматизация</li>
<li>Визуализация лемм</li>
<li>Создание признаков</li></ul>
<li>Валидация и тестирование моделей.
  
## Библиотеки и инструменты:
<li>PyTorch.
<li>NLTK.
<li>Spacy.
<li>Detoxify.
<li>Bert, ToxicBert.
<li>Scikit-Learn: LogisticRegression, TfidfVectorizer, CountVectorizer. 
<li>CatBoostClassifier.
<li>Transformers.
<li>Pandas. 
<li>Matplotlib. 
<li>Seaborn. 
<li>Wordcloud.
<li>Numpy. 
<li>IO, OS, Requests.
