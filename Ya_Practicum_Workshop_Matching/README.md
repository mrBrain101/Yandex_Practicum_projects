# Мэтчинг товаров.
## Результат работы.
  - Значение целевой метрики `accuracy@5` 0.71 было достигнуто с использованием модели `FAISS` с параметрами
    - с кол-вом кластеров 50;
    - индексом `IVFHNSWFLAT`;
  - на смасштабированных с помощью `RobustScaler` данных;
  - с удалением признаков, распределённых ненормально.

## Задача.
  - Был разработан алгоритм, который для всех товаров из `validation.csv` находит 5 похожих из `base.csv`.

## Использовавшиеся в тестировании модели. 
`FAISS` / `ANNOY`.

## Данные.
- Размер датасетов:
  - `df_base`: 2918139 X 72 с идентификаторами объектов в индексе;
  - `df_train`: 100000 X 73, в т.ч. признак ответов, и с идентификаторами объектов в индексе;
  - `df_val`: 100000 X 72 с идентификаторами объектов в индексе;
  - `df_val_answers`: 100000 X 1 - признак ответов с идентификаторами объектов в индексе.
- Распределение признаков.
  - Признаки 6, 21, 25, 33, 44, 59, 65, 70 имеют ненормальное распределение. Остальные признаки имеют распределения приближенные к нормальному. <br>
  Из-за невозможности идентификации признаков и неэффективности преобразований распределений признаков с точки зрения целевой метрики, признаки с ненормальным распределением были удалены.
- Выбросы / аномалии.
  - Почти во всех признаках среднее близко к медиане и присутствует минимальный процент выбросов. Удаление / замена выбросов средним не оказались эффективнымы.
- Признаки 33 и 44 дискретны, возможно категориальны, т.к. имеют менее 1% и 2% уникальнах значений соответственно. Была проведена тестовая кластеризация по признаку `33`, которая не оказалась эффективной.
- Корреляция признаков / мультиколлинеарность.
  - Корреляция признаков не обнаружена.
## Рекомендации / возможные направления улучшения точности мэтчинга.
  - Проведение более развёрнутого анализа кластеров / признаков.
  - Оптимизация реализации связки "простых" алгоритмов `KMeans` + `NearestNeigbors`.