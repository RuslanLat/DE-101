[Обратно в содержание домашних заданий:leftwards_arrow_with_hook:](https://github.com/RuslanLat/DE-101/blob/main/README.md)

# Задание модуля 2

Курс обучения [Getting Started with Analytics (Data) Engineering](https://datalearn.ru/kurs-po-getting-start-with-data-engineering)

[Задание](https://github.com/RuslanLat/DE-101/blob/main/Module02/task.md)

## Установка БД

База данных **установлена**

![install_db](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/install_db.png)

## Загрузка данных в БД

Создание таблиц:
* заказы - **'orders'**
* менеджеры - **'people'**
* возвраты - **'returns'**

[Notebook](https://github.com/RuslanLat/DE-101/blob/main/Module02/greate_table.ipynb) с **SQL** запросами

Загрузка данных [Sample - Superstore.xls](https://github.com/RuslanLat/DE-101/blob/main/Module02/data/Sample%20-%20Superstore.xls) в БД

[Notebook](https://github.com/RuslanLat/DE-101/blob/main/Module02/insert_data.ipynb) с **SQL** запросами

## SQL запросы

[Notebook](https://github.com/RuslanLat/DE-101/blob/main/Module02/select_data.ipynb) с **SQL** запросами

* Total Sales
* Total Profit
* Profit Ratio
* Profit per Order 
* Sales per Customer
* Avg. Discount
* Monthly Sales by Segment
* Monthly Sales by Product Category
* Sales by Product Category over time
* Sales and Profit by Customer
* Customer Ranking
* Sales per region

## Нарисовать модель данных в SQLdbm

Концептуальная модель данных

![conceptual_model](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/conceptual_model.png)

Логическая модель данных

![conceptual_model](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/logical_model.png)

[Схема данных](https://github.com/RuslanLat/DE-101/blob/main/Module02/schema.xml)

Для создания схемы данных я использовал [NoSQL DB Schema Modeling](https://nosqldbm.ru/)

## База данных в облаке

![db_in_cloud](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/db_in_cloud.png)

Схемы Баз данных:
* **Stagen** - STORAGE LAYER

[Notebook](https://github.com/RuslanLat/DE-101/blob/main/Module02/stagen_storage_layer.ipynb) с **SQL** запросами

* **BL model** - STORAGE LAYER

[Notebook](https://github.com/RuslanLat/DE-101/blob/main/Module02/bl_model_storage_layer.ipynb) с **SQL** запросами

* **SQL Query** - BUSINESS LAYER

[Notebook](https://github.com/RuslanLat/DE-101/blob/main/Module02/sql_query_business_layer.ipynb) с **SQL** запросами

## Нарисовать графики в Google Sheets

Подключение к Базе данных

![connect_db](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/connect_db.png)

Экспорт данных - **SQL Query**

![select_data](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/select_data.png)

Вывод данных в **Goodle Sheets**

![show_data](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/show_data.png)

[Дашборд в Google Sheets](https://docs.google.com/spreadsheets/d/1OjKzOkvcwMfsiGWqjpnlnX3fDj8IN1wk6NP7-HTXJXY/edit?usp=sharing) **Superstore**

![dashboard](https://github.com/RuslanLat/DE-101/blob/main/Module02/images/dashboard.png)

Руслан Латипов <img src="https://github.com/RuslanLat/DE-101/blob/main/Module02/images/telegram_icon.png" width="15"> @rus_lat116