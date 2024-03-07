# **Тема проекта**: Использование современных средств анализа и визуализации данных для исследования рынка труда по информации из базы данных Федеральной службы  по труду и занятости населения РФ. 
## **Цель**: Изучить и проанализировать представленные данные и сформировать интерактивный отчет, дающий представление о выбранной предметной области исследования.

### **Задачи**:   

1. Изучить литературу, касающуюся темы исследования;    

2. Исследовать данные для дальнейшей загрузки в базу; 

3. Создать и наполнить базу данных MySQL; 

4. Осуществить необходимую выгрузку данных под конкретные запросы для дальнейшей визуализации;   

5. Визуализировать данные. 

#### Инструменты: Jupyter Notebook, PyCharm, MySQL Workbench, Python, Pandas, MS EXCEL, компонент Windows Блокнот, MS Power BI, MySQL, язык запросов DAX.  

### **Структура дипломного проекта**:   

_Оглавление_  

 

**Глава 1. Системные характеристики ноутбуков. (~1 стр)**  

1.1 На начальном этапе работы.

1.2 Основной ноутбук для работы.

**Глава 2. Первичный анализ данных в среде разработки Jupyter Notebook с использованием библиотеки Pandas. (~5 стр)**  

2.1 Подсчет максимального количества символов в одной ячейке данных, которое может быть в заданном столбце.

2.1.1 Выведение ячейки с максимальной длиной по заданной длине. Для проверки работы кода.

2.2 Ознакомление с примерным содержимым столбца через вывод значений нескольких ячеек, выбранных случайным образом.

2.3 Подсчет количества всех имеющихся уникальных значений столбца таблицы.

2.4 Вывод списка всех заголовков столбцов на консоль;

2.5 Вывод заданного количества строк таблицы для дальнейшего ознакомления.

2.6 Вывод количества пустых (не имеющих значений) ячеек в указанном столбце.

2.7 Подсчет общего количества строк таблицы.

2.8 Изучение типов данных в каждом из столбцов.

**Глава 3. Создание и наполнение базы данных MySQL в среде разработки PyCharm на языке программирования Python. (~6 стр)** 

3.1 Создание базы данных MySQL.

3.2 Основной скрипт построчной загрузки данных в MySQL.

3.3 Вывод на консоль ошибки, препятствующей загрузке файла.

3.4 Анализ ошибок, препятствующих загрузке данных CSV файла в БД MySQL.

3.4.1 Наличие одинарных кавычек.

3.4.2 Наличие точек с запятыми и '\n' в текстовых сообщениях столбцов CSV файла. 

3.4.3 Наличие символов обратной косой черты «обратный слэш» непосредственно в конце строки перед разделителем точкой с запятой.

3.5 Разделение CSV файла на CSV файлы меньшего размера согласно указанному количеству строк.

3.6 Типы данных MySQL.

3.6.1 Изменение формата даты и регулярные выражения.

3.7 Дубликаты строк в таблицах.

3.8 Индекс как средство увеличения производительности в работе с БД.

3.9 Итоговое описание загруженной БД.

**Глава 4. Архитектура данных. (~6 стр)** 

4.1 Primary Data Layer (ODS)

4.2 Core Data Layer (DDS)

4.3 Data Mart Layer (DM)

**Глава 5. Выгрузка и визуализация данных (~4 стр)**

5.1 Выгрузка данных для последующей визуализации.

5.2 Работа с данными в MS Power BI.

_Заключение (~ 4 стр)_ 

_Список используемой литературы_ 

_Приложения_
