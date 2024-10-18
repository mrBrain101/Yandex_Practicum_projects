[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)



# Yandex Практикум: Курс "Специалист по Data Science плюс".

## Описание проектов по обработке естественного языка.
| # | Направление | Название (ссылка) | Описание | Стек |
|:--|:--|:--|:--|:--|
| 01 | ![](https://img.shields.io/badge/CV-367539) ![](https://img.shields.io/badge/NLP-323ea8) ![](https://img.shields.io/badge/ML-753636)| [Поиск изображений по запросу.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/677e8370dee0aadea6a333ea7df9ac2beb0f571f/CV_NLP_Prompt_image_matching)| Для демонстрационной версии модели мэтчинга изображений и запроса была обучена MVP-модель, способная по векторному представлению изображения и векторному представлению текста, выдать число от 0 до 1 — показать, насколько текст и картинка подходят друг другу.| Python.<br>PyTorch, TorchVision. <br>Scikit-Learn: LinearRegression, ElasticNet. <br>CatBoostRegressor.<br>Spacy.<br>PIL.<br>Transformers.<br>Pandas. <br>Matplotlib, Seaborn. <br>Numpy. <br>OS, Requests.|
| 02 | ![](https://img.shields.io/badge/NLP-323ea8) |[Классификация токсичных комментариев.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/677e8370dee0aadea6a333ea7df9ac2beb0f571f/NLP_Toxic_Commentaries_Classification)|Для классификации токсичных комментариев была использована модель оценки токсичности комментариев _toxic-bert_ и применена логистическая регрессия: _F1_= 0.93. |Python.<br>PyTorch.<br>NLTK.<br>Spacy.<br>Detoxify.<br>Bert, ToxicBert.<br>Scikit-Learn: LogisticRegression, TfidfVectorizer, CountVectorizer. <br>CatBoostClassifier.<br>Transformers.<br>Pandas. <br>Matplotlib, Seaborn. <br>Wordcloud.<br>Numpy. <br>IO, OS, Requests.|