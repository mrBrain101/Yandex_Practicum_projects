[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

# Прогнозирование оттока клиентов в телекоме.

## Проблема.
Бинарная классификация оттока клиентов в телекоме.<br>
## Решение.
Для предсказания оттока клиентов, была построена модель, с _ROC AUC_ = 0.84, _accuracy_ - 0.77.

Поскольку проект содержит большое количество графиков, GitHub не сможет его отобразить.
Вы можете просмотреть проект в [NBViewer по этой ссылке]( https://nbviewer.org/github/mrBrain101/Yandex_Practicum_projects/blob/faf87fda0586f77c4366af3ccdb27349053868a3/ML_Telecom_Churn_Prediction/Ya_Practicum_ML_Telecom_Churn_Prediction_distr_RUS.ipynb).<br>

[Ссылка на проект.](https://github.com/mrBrain101/Yandex_Practicum_projects/blob/faf87fda0586f77c4366af3ccdb27349053868a3/ML_Telecom_Churn_Prediction/Ya_Practicum_ML_Telecom_Churn_Prediction_distr_RUS.ipynb)

## Этапы:
<li>Загрузка, объединение, очистка и предварительная обработка данных.
<li>Исследовательский анализ данных. 
<li>Создание и отбор признаков. 
<li>Валидация и тестирование моделей.
  
## Библиотеки и инструменты:
<li>OS, Multiprocessing, SQLAlchemy, Psycopg2.
<li>Pandas, Numpy.
<li>Phik, Shap.
<li>Matplotlib, Seaborn.
<li>Scikit-Learn, CatBoost, Category Encoders.
<li>ydata_synthetic.
<li>Optuna, TQDM.