[![ru](https://img.shields.io/badge/lang-ru-red.svg)](README.md)

# Realty price prediction. 
Building an ML model that determines the prices of the real estate for the California 1990 housing dataset. All the data manipulation is done with Spark (PySpark).<br>

[Project permalink.]()

## Steps:
<li>Spark session initialization and packages loading.
<li>Data loading.
<li>EDA. 
<li>Preprocessing. 
<li>Models validation ant testing.
<li>Spark session stopping.
<li>Project summary.
  
## Utilized libraries and tools:
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
