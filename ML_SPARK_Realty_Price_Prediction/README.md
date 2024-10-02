[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

# Предсказание стоимости жилья. 
Построение ML-модели, определяющей цены на недвижимость для набора данных по жилью Калифорнии 1990 года. Все манипуляции с данными выполняются с помощью Spark (PySpark).<br>

[Ссылка на проект.]()

## Краткое содержание:
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