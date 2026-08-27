# 1С -разработчик

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Филоненко+Александр+1С+разработчик)](https://git.io/typing-svg)


### *В репозитории хранятся проекты(бизнес-задачи), выполненные по направлению 1C - разработчик.*
#### Источники данных не приложены.



|   № |    Бизнес - задача  |   Дополнительные пояснения |  Описание |
|:----|:---------------------|:---------|:----------------------|
|   1.  |   [Разработать систему, предназначенную для компании, которая занимается изготовлением моторных и парусных яхт.](https://github.com/brrndalex/1C_Developer/tree/main/Business%20task_1)                   |  1. В "ручном" режиме: Получить "сырые" данные из API и сохранить их в MinioS3 в форматах json и parquet. Из MinioS3 загрузить данные в формате parquet в DWH, во временные таблицы GreenPlum. И в заключении из временных таблиц загрузить данные в спроектированные объекты Data Vault. 2. С помощью Аpache Airflow объединить все этапы в один общий, непрерывный поток, конвейер данных.       |   Python (библиотеки: requests, boto3, json, pandas, pyarrow). SQL. Командная строка Linux. Docker compose. Minio. Greenplum. DBT. Data Vault 2.0. Apache Airflow. VSCode. Draw.io. DBeaver.                    |
|   2.  |    [Разработать систему, предназначенную для сотрудников компании, которая занимается организацией туристических поездок в различные страны.](https://github.com/brrndalex/1C_Developer/tree/main/Business%20task_2)                          |   Подготовить данные в HDFS. Загрузить данные в топик Apache Kafka. Переписать запрос для сборки витрины с SQL на PySpark. Сформировать пайплайн, считывая Apache Spark-ом данные из HDFS и из Apache Kafka. Сохранить результат работы пайплайна каждую минуту в формате parquet в произвольную HDFS-директорию.      |  Python (библиотеки: confluent_kafka(Producer), json, csv), Apache Spark (PySpark), Docker compose, Hadoop (HDFS), Apache Kafka. Jupyter Notebook.                     |  






E-mail: sashasanyashura@yandex.ru
