# 1С -разработчик

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Филоненко+Александр+1С+разработчик)](https://git.io/typing-svg)



[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=4EF752&width=435&lines=%D0%A4%D0%B8%D0%BB%D0%BE%D0%BD%D0%B5%D0%BD%D0%BA%D0%BE;%D0%90%D0%BB%D0%B5%D0%BA%D1%81%D0%B0%D0%BD%D0%B4%D1%80)](https://git.io/typing-svg)

### *В репозитории хранятся проекты, выполненные по направлению 1C - разработчик.*
#### Источники данных не приложены.

|   № |    Название проекта  |   Описание |  Навыки и инструменты |
|:----|:---------------------|:---------|:----------------------|
|   1.  |   [ЗАГРУЗКА ДАННЫХ из API в DWH.](https://github.com/brrndalex/Data-Engineer-Projects/tree/main/%D0%97%D0%90%D0%93%D0%A0%D0%A3%D0%97%D0%9A%D0%90%20%D0%94%D0%90%D0%9D%D0%9D%D0%AB%D0%A5%20%D0%B8%D0%B7%20API%20%D0%B2%20DWH.)                   |  1. В "ручном" режиме: Получить "сырые" данные из API и сохранить их в MinioS3 в форматах json и parquet. Из MinioS3 загрузить данные в формате parquet в DWH, во временные таблицы GreenPlum. И в заключении из временных таблиц загрузить данные в спроектированные объекты Data Vault. 2. С помощью Аpache Airflow объединить все этапы в один общий, непрерывный поток, конвейер данных.       |   Python (библиотеки: requests, boto3, json, pandas, pyarrow). SQL. Командная строка Linux. Docker compose. Minio. Greenplum. DBT. Data Vault 2.0. Apache Airflow. VSCode. Draw.io. DBeaver.                    |
|   2.  |    [ЗАГРУЗКА ДАННЫХ, из Hadoop (HDFS), Apache Kafka  с использованием Apache Spark в Hadoop (HDFS).](https://github.com/brrndalex/Data-Engineer-Projects/tree/main/%D0%97%D0%90%D0%93%D0%A0%D0%A3%D0%97%D0%9A%D0%90%20%D0%94%D0%90%D0%9D%D0%9D%D0%AB%D0%A5%2C%20%D0%B8%D0%B7%20Hadoop%20(HDFS)%2C%20Apache%20Kafka%20%D1%81%20%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%D0%BC%20Apache%20Spark%20%D0%B2%20Hadoop%20(HDFS).)                          |   Подготовить данные в HDFS. Загрузить данные в топик Apache Kafka. Переписать запрос для сборки витрины с SQL на PySpark. Сформировать пайплайн, считывая Apache Spark-ом данные из HDFS и из Apache Kafka. Сохранить результат работы пайплайна каждую минуту в формате parquet в произвольную HDFS-директорию.      |  Python (библиотеки: confluent_kafka(Producer), json, csv), Apache Spark (PySpark), Docker compose, Hadoop (HDFS), Apache Kafka. Jupyter Notebook.                     |  






E-mail: sashasanyashura@yandex.ru
