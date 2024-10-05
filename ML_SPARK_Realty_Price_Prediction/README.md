[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

# Предсказание стоимости жилья. 

## Проблема.
Построение ML-модели, определяющей цены на недвижимость для набора данных по жилью Калифорнии 1990 года. Все манипуляции с данными выполняются с помощью Spark (PySpark).
## Решение.
Для определения цен на недвижимость были построены модели регрессии.

[Ссылка на проект.](https://github.com/mrBrain101/Yandex_Practicum_projects/blob/84215eae9b2a40463224dc69158934a71c7380b0/ML_SPARK_Realty_Price_Prediction/Ya_Practicum_ML_SPARK_Realty_Price_Prediction_distr_RUS.ipynb)

## Этапы:
<li>Инициализация сессии Spark и загрузка пакетов.
<li>Загрузка данных.
<li>Исследовательский анализ данных. 
<li>Предварительная обработка. 
<li>Валидация и тестирование моделей.
<li>Остановка сессии Spark.
<li>Анализ релультатов работы.
  
## Библиотеки и инструменты:
<li>PySpark:
<ul>
<li>SQL:
	<ul>
	<li>SparkSession
	<li>functions
	</ul>
<li>MLib:
	<ul>
	<li>regression: LinearRegression
	<li>stat: Correlation
	<li>feature: StringIndexer
	<li>feature: OneHotEncoder
	<li>feature: VectorAsembler
	<li>feature: SdandardScaler
	<li>clustering: KMeans for feature generation
	<li>evaluation: RegresionEvaluator
	</ul>
</ul>
<li>Pandas. 
<li>Numpy.
<li>Matplotlib. 
<li>Seaborn.
