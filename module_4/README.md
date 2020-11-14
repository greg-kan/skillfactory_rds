# Проект 4. Компьютер говорит «Нет»
## Юнит 4. Основные алгоритмы машинного обучения. Часть I.
### skillfactory_rds  
![https://img.shields.io/badge/Python-3.7.4-blue](https://img.shields.io/badge/Python-3.7.4-blue)

## Оглавление  
[1. Описание модуля](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Описание-модуля)  
[2. Какой кейс решаем?](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Краткая-информация-о-данных)  
[3. Этапы работы над проектом](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Этапы-работы-над-проектом)  
[4. Результат](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Результат)  

### Описание модуля  
В этом модуле были изучены основные алгоритмы ML, такие как Линейная и Логистическая регрессии и рассмотрено использование метрик качества (ROC-AUC, F1, Acuracy, ...).
Данный проект является результатом прохождения модуля.

:arrow_up:[к оглавлению](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Оглавление)

### Какой кейс решаем?
За 48 часов разработать модель банковского скоринга, предсказыющую вероятность дефолта клиента. 

**Условия соревнования:**  
Тестовая выборка представлена в ЛидерБорде целиком.  
Поэтому лучшие и победные решения буду проверяться на их "адекватность" (чтоб не было подгонки под тестовую выборку).  
Разрешено использовать любые ML алгоритмы и библиотеки (кроме DL).  
Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.  

**Метрика качества:**
Результаты оцениваются по площади под кривой ROC AUC

:arrow_up:[к оглавлению](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Оглавление)

### Краткая информация о данных
Датасет содержит информацию о заемщиках, которые уже брали кредиты (повторных клиентов).  
Вам предоставлена информация из анкетных данных заемщиков и факт наличия дефолта.  
Описание полей датасета:  
- client_id	- идентификатор клиента  
- education	- уровень образования (ACD - academy - академическое, PGR - post-graduate - магистратура, GRD - graduate - бакалавриат, SCH - school - среднее)  
- sex	- пол заёмщика  
- age	- возраст заёмщика  
- car	- флаг наличия автомобиля  
- car_type	- флаг автомобиля-иномарки  
- decline_app_cnt	- количество отказанных прошлых заявок  
- good_work	- флаг наличия «хорошей» работы  
- bki_request_cnt	- количество запросов в БКИ  
- home_address	- категоризатор домашнего адреса  
- work_address	- категоризатор рабочего адреса  
- income	- доход заёмщика  
- foreign_passport	- наличие загранпаспорта  
- sna - связь заемщика с клиентами банка  
- first_time - давность наличия информации о заемщике  
- score_bki - скоринговый балл по данным из БКИ  
- region_rating - рейтинг региона  
- app_date - дата подачи заявки  
- default	- наличие дефолта  

:arrow_up:[к оглавлению](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Оглавление)

### Этапы работы над проектом  
- 1. Загрузка данных и предварительный анализ
- 2. Анализ переменных
- 3. Подготовка данных к использованию в моделе
- 4. Построение модели
- 5. Метрики качества
- 6. Подбор гиперпараметров
- 7. Submission
- 8. Итоги

:arrow_up:[к оглавлению](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Оглавление)

### Результат  
ROC-AUC on Caggle: 0.73646

:arrow_up:[к оглавлению](https://github.com/greg-kan/skillfactory_rds/blob/master/module_4/README.md#Оглавление)
