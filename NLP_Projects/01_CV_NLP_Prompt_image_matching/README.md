[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

# Поиск изображений по запросу. 

## Проблема.
Разработка демонстрационной версии поиска изображений по текстовому запросу.
## Решение.
Для демонстрационной версии была обучена MVP-модель, способная по векторному представлению изображения и векторному представлению текста, выдать число от 0 до 1 — показать, насколько текст и картинка подходят друг другу.

[Ссылка на проект.](https://github.com/mrBrain101/Yandex_Practicum_projects/blob/8464bd0b4e419bac97d342b8dbf2d90646ce9f6a/CV_NLP_Prompt_image_matching/Ya_Practicum_CV_NLP_prompt_image_search_distr_RUS.ipynb)

## Этапы:
<li>Исследовательский анализ данных. 
<li>Создание эмбеддингов изображений и текстов и их объединение. 
<li>Валидация и тестирование моделей.
  
## Библиотеки и инструменты:
<li>PyTorch, TorchVision.
<li>Scikit-Learn: LinearRegression, ElasticNet. 
<li>CatBoostRegressor.
<li>Spacy.
<li>PIL.
<li>Transformers.
<li>Pandas. 
<li>Matplotlib. 
<li>Seaborn. 
<li>Numpy. 
<li>OS, Requests.
