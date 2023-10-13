# Lecturer
Timur Bosenko M. (bosenkotm@mgpu.ru)

Здесь Вы можете найти все материалы по дисциплине **`Инструменты аналитика данных для решения прикладных задач`**. 

Курс представляет собой  введение в концепции анализа данных, роль аналитика данных и инструменты, которые используются для выполнения задач. Вы получите представление об экосистеме данных и основах анализа данных, таких как сбор данных или интеллектуальный анализ данных. Познакомитесь с современными инструментами аналитика данных, принципами работы инструментов бизнес-аналитики и BI-решений. В конце каждого урока будут практические упражнения, которые мы начнем вместе и которые должны быть завершены к следующей встрече. Так что будьте внимательны, и если Вы не успеваете, не стесняйтесь задавать вопросы в конце каждого урока.

**`ВАЖНО!`** Для работы с `jupyter` ноутбуками предварительно необходимо пройти курс [python-data-analysis-tools](https://github.com/BosenkoTM/PDA).

## Программное обеспечение 

 - **`Google Colaboratory`** — бесплатная среда, чтобы писать код в jupyter notebook. [Google Colaboratory](  https://colab.research.google.com/).
 - **`Студия данных Google`** — cервис визуализации и анализа данных(En). [DataStudio](https://datastudio.google.com/navigation/reporting).
 - **`Yandex DataLens`** — cервис визуализации и анализа данных(Ru). [DataLens](https://datalens.yandex.ru/).

## Текущая успеваемость

 [АДЭУ-221](https://docs.google.com/spreadsheets/d/1jSBjDeu23q6fdkR9OyvqIYbHeZpov9XTWNaDsHRcIF4/edit?usp=sharing)

## Data analytics tools for solving applied problems

- `lecture 01` Intro:
    -  [Introduction to Data analytics](/lectures/lecture_01.pdf)
  
    -  [Product analytics](https://youtu.be/Vy_rq-x9QEo)
     
-  `Practice 01`: 
    -  01-1 [Визуализация данных из CSV-файла](https://cloud.yandex.ru/docs/datalens/tutorials/data-from-csv-visualization). [Индивидуальное задание](/practice/ex_01_1/01ex.md).
    -  01-2 [Product analytics](/practice/ex_01_2).
    
- `lecture 02`: 
    - [Инструменты интеграции и удаление файлов (ETL)](/lectures/lecture_02.pdf)
- `Practice 02`: 
    - `02En` [Работа в ETL-системе Talend](/practice/ex_02/pr_02_read_fileCSV_talend.pdf). Репозиторий программы [тут](https://disk.yandex.ru/d/jELYUXeI9HEEmg)
  
    - `02Ru`  [POLYMATICA BI В ОБЛАКЕ](https://partners.platform.polymatica.ru/auth?redirect=https%253A%252F%252Fpartners.platform.polymatica.ru%252F)
    -  **02-1** [Polymatica Dashboards: загрузка данных из файла и работа с датасетом](https://www.youtube.com/watch?v=83iCC4unHsE&list=PLjiEjSNywDXuZgIgd6PjlIbLkXGiqlP2k&index=2);
    - **02-2** [Polymatica Dashboards: cоздание источника](https://www.youtube.com/watch?v=BrIqTrhBs84&list=PLjiEjSNywDXuZgIgd6PjlIbLkXGiqlP2k&index=3);
    - **02-3** [Polymatica Dashboards: загрузка датасета из источника](https://www.youtube.com/watch?v=vth0efKfzyA&list=PLjiEjSNywDXuZgIgd6PjlIbLkXGiqlP2k&index=4);
    - **02-4** [Polymatica Dashboards: настройка фильтров](https://www.youtube.com/watch?v=Q9tC6PsyvmQ&list=PLjiEjSNywDXuZgIgd6PjlIbLkXGiqlP2k&index=6);
    - **02-5** [Polymatica Dashboards: объединение датасетов](https://www.youtube.com/watch?v=3MNmzGKcRKM&list=PLjiEjSNywDXuZgIgd6PjlIbLkXGiqlP2k&index=9).
    
- `lecture 03`:
    - [Архитектура хранилищ данных: традиционная и облачная](/lectures/lecture_03.pdf)
-  `Practice 03`: 
    - 03 [Архитектура хранилищ данных: традиционная и облачная](/practice/ex_03/ex_3.pdf).
    -  Репозиторий программы [тут](https://disk.yandex.ru/d/jELYUXeI9HEEmg)
    - Вам необходимо скачать и запустить Pentaho Data Integration Community Edition [скачать](https://sourceforge.net/projects/pentaho/).
    - Pentaho DI требует установку Java 8.
    - Скачать архив и распаковать его. Вам нужно запустить `spoon.sh` для Linux/Mac и `spoon.bat` для Windows.
    -  Установка `Pentaho DI` на примере Windows 10  [здесь](https://www.youtube.com/watch?v=RL-EZCi51gc&feature=youtu.be&ab_channel=DataLearn)

#### Самостоятельная работа 1
1. Скачать и запустить Pentaho DI, [отсюда](https://sourceforge.net/projects/pentaho/).
2. [Скачать примеры Pentaho jobs](https://github.com/Data-Learn/data-engineering/tree/master/DE-101%20Modules/Module04/DE%20-%20101%20Lab%204.4) для `Staging` и `Dimension Tables`.
3. Создайте еще одну трансформацию, в которой вы создадите `sales_fact` таблицу.

- `lecture 04`:
    - [Marketing Analytics - кейсы](https://github.com/pilosI/python_data_analysis#%D1%83%D1%87%D0%B5%D0%B1%D0%BD%D1%8B%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B-%D0%BF%D0%BE-%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%D1%83-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%D0%B2-jupyter-notebook)
- `Practice04`: 
    - 04-01 [Marketing Analytics](/marketing_analytics_students.ipynb).
    - 04-02 [Marketing Analytics vs MySQL](https://colab.research.google.com/drive/1ZFauMnc7JSRUGDEdor0EC6BAUe_YGVwt?usp=sharing).
    
- `lecture 05`:
    - [Business Intelligence-аналитика Data Prep & Alteryx Designer ](/lectures/lecture_05.pdf)
    
- `Practice 05`:
   Необходимо построить в `Tableau Prep Flow`, `Alteryx Workflow`потоки данных ([скачать данные](/data)) и сохранить результат в своем `git`. Вы можете использовать данные, подключившись к БД `Postgres` или БД `My SQL`, в которую мы загружали данные. Альтернативно, можете просто повторить существующие задания из Alteryx/Tableau tutorial, чтобы понять как работает инструмент.

    [Видеолекция по инструментам аналитики данных](https://www.tableau.com/support/releases/prep/2022.2.3#esdalt). 
    Репозиторий программы [тут](https://disk.yandex.ru/d/jELYUXeI9HEEmg)

- `lecture 06`:
   - [Python инструменты аналитика данных]();
- `Practice 06`:    
    
- `lecture 07`:
    - [Инструменты аналитики Airflow + task on lecture_06](/lectures/lecture_06_airflow_day_1.pdf)
    
- `Practice 07`: 
    -  [Live COVID-19 tracker with Airflow](https://towardsdatascience.com/your-live-covid-19-tracker-with-airflow-and-github-pages-658c3e048304).
    -  [Live COVID-19 tracker with Airflow GITHUB](https://github.com/hectoramirez/Covid19)
    
- `lecture 07`:
    - [Оркестр процессов обработки данных с помощью Apache Airflow](/lectures/lecture_07_airflow_day_2_orcestr.pdf)

### Дополнительные материалы для изучения
#### ETL Компоненты и начало работы с ETL на примере Pentaho Data Integration
1. Видео лекция - теория - [ETL Компоненты](https://youtu.be/-oCBttnefMQ). 
2. Видео лекция - практика - [Начало работы с Pentaho DI](https://youtu.be/-oCBttnefMQ?t=2087)
3. [Видео по основам Pentaho DI](https://youtu.be/K3X9wIC0jO8) и [ссылка на исходные файлы из видео](https://drive.google.com/file/d/1yw0E7Gqm4Rocui_pQYPdfmmnFtGfx3LY/view?usp=sharing)
#### Tableau prep
1. [2023 Начало работы с Tableau prep](https://help.tableau.com/current/prep/en-us/prep_get_started.htm);
2. [2023 Tableau Prep Help](https://disk.yandex.ru/d/BjbXWdqjH0jzyA);
3. Carl Allchin [ 2020 Tableau Prep: Up & Running](https://disk.yandex.ru/i/Qpjx0mtLurwkcw);
4. [2019 A-Practitioners-Guide-to-Tableau-prep-Builder](https://docs.yandex.ru/docs/view?tm=1665697499&tld=ru&lang=en&name=A-Practitioners-Guide-to-Tableau-prep-Builder.pdf&text=Tableau%20Prep&url=https%3A%2F%2Fresources.useready.com%2Fwp-content%2Fuploads%2F2019%2F08%2FA-Practitioners-Guide-to-Tableau-prep-Builder.pdf&lr=213&mime=pdf&l10n=ru&sign=6de6f2866532daf9d67052c949d1830f&keyno=0&nosw=1&serpParams=tm%3D1665697499%26tld%3Dru%26lang%3Den%26name%3DA-Practitioners-Guide-to-Tableau-prep-Builder.pdf%26text%3DTableau%2BPrep%26url%3Dhttps%253A%2F%2Fresources.useready.com%2Fwp-content%2Fuploads%2F2019%2F08%2FA-Practitioners-Guide-to-Tableau-prep-Builder.pdf%26lr%3D213%26mime%3Dpdf%26l10n%3Dru%26sign%3D6de6f2866532daf9d67052c949d1830f%26keyno%3D0%26nosw%3D1).
5. [Начало работы с Alteryx Designer](https://help.alteryx.com/learn/learningguide.html).
#### Apache Airflow
1. [Введение в Apache Airflow](https://khashtamov.com/ru/apache-airflow-introduction/) (Русский)
2. [Как мы оркестрируем процессы обработки данных с помощью Apache Airflow](https://habr.com/ru/company/lamoda/blog/518620/) (Русский)
3. [Apache Airflow: делаем ETL проще](https://habr.com/ru/post/512386/) (Русский)
4. [ETL процесс получения данных из электронной почты в Apache Airflow](https://habr.com/ru/post/495676/) (Русский)
5. [Getting started with Apache Airflow](https://towardsdatascience.com/getting-started-with-apache-airflow-df1aa77d7b1b) (English)
#### Apache NiFi
1. [Apache NiFi: что это такое и краткий обзор возможностей](https://habr.com/ru/company/rostelecom/blog/432166/) (Русский)
2. [Динамическое создание кластера Apache NiFi](https://habr.com/ru/post/331444/) (Русский)
3. [Apache NIFI — Краткий обзор возможностей на практике](https://habr.com/ru/post/465299/) (Русский)
4. [How Apache Nifi works — surf on your dataflow, don’t drown in it](https://medium.com/free-code-camp/nifi-surf-on-your-dataflow-4f3343c50aa2)
5. [Побег от скуки — процессы ETL](https://habr.com/ru/post/508620/) (Русский)
#### Data Build Tool (dbt) tool 
1. [Data Build Tool или что общего между Хранилищем Данных и Смузи](https://habr.com/ru/company/otus/blog/501380/) (Русский)
2. [DBT: A new way to transform data and build pipelines at The Telegraph](https://medium.com/the-telegraph-engineering/dbt-a-new-way-to-handle-data-transformation-at-the-telegraph-868ce3964eb4) (English)
3. [What, exactly, is dbt?](https://blog.getdbt.com/what--exactly--is-dbt-/) (English)
4. [Работа с dbt на базе Google BigQuery](https://habr.com/ru/post/542008/) (Русский)
5. [Сквозная Аналитика на Azure SQL + dbt + Github Actions + Metabase](https://habr.com/ru/post/538106/) (Русский)

#### Luigi
1. [Строим Data Pipeline на Python и Luigi](https://khashtamov.com/ru/data-pipeline-luigi-python/) (Русский)
2. [Обзор фреймворка Luigi для построения последовательностей выполнения задач](https://habr.com/ru/company/otus/blog/339904/) (Русский)
3. [Airbnb’s Airflow Versus Spotify’s Luigi](https://medium.com/better-programming/airbnbs-airflow-versus-spotify-s-luigi-bd4c7c2c0791) (English)
4. [Data pipelines, Luigi, Airflow: everything you need to know](https://towardsdatascience.com/data-pipelines-luigi-airflow-everything-you-need-to-know-18dc741449b7) (English)


## Теоретические вопросы

1.	Виды аналитики данных. Сравнительный анализ.
2.	Инструменты аналитики данных.
3.	Экосистема данных.
4.	Обзор экосистемы Data Analyst.Типы данных.
5.	Понимание различных типов форматов файлов.Источники данных.
6.	Языки для специалистов по данным.
7.	Обзор репозиториев данных.
8.	СУБД.NoSQL.
9.	Витрины данных, озера данных, ETL и конвейеры данных.
10.	Основы больших данных.
11.	Инструменты обработки больших данных.
12.	Инструменты сбора и обработки данных.
13.	Источники данных. Как собирать и импортировать данные.
14.	Что такое обработка данных. Инструменты для обработки данных. Очистка данных.
15.	Визуализация данных.
16.	Программное обеспечение для визуализации и информационной панели.

## ТЕСТ 1. Зачетное тестирование. 
[ССЫЛКА ДЛЯ ВХОДА](https://docs.google.com/forms/d/e/1FAIpQLSd0hfJDgqL1pNQE_np1S0V1_FVY7h_1Dvki7b_yimaj4Fnb8A/viewform?usp=sf_link)


## Зачетное практическое задание

<br>

|№|Название проекта|Сфера|Описание|Стек|
|:-----:|-----|:-----:|-----|:-----:|
|1|[Исследование надёжности заёмщиков](https://github.com/dsibi/yandex_praktikum_da/tree/main/assess_reliability_of_bank_borrowers)|Финансы|Предобработка и анализ данных; лемматизация; исследовательский анализ данных| `Python` `pymystem3` `Pandas` `NumPy` |
|2|[Исследование объявлений о продаже квартир](https://github.com/dsibi/yandex_praktikum_da/tree/main/ads_for_sale_of_apartments_research)|Недвижимость|Предобработка данных; поиск корреляций| `Pandas` `Matplotlib` `NumPy`|
|3|[Определение перспективного тарифа для телеком компании](https://github.com/dsibi/yandex_praktikum_da/tree/main/determination_of_perspective_tariff)|Телеком|Объединение данных из пяти таблиц в одну; изучение аномалий в данных; исследовательский анализ данных; статистический анализ данных | `Pandas` `Matplotlib` `display` `math` `NumPy` `SciPy` `Statsmodels`|
|4|[Исследование рынка видеоигр](https://github.com/dsibi/yandex_praktikum_da/tree/main/videogames_market_research)|Интернет-магазин|Предобработка данных; анализ данных; составление портрета пользователей каждого региона; проверка гипотез; выявление параметров, определяющих успешность видеоигр в разных регионах мира; подготовка отчета в целях планирования рекламных кампаний для магазина компьютерных игр |`Matplotlib` `Pandas` `Python` `NumPy` `SciPy` `downcast` `warnings`|
|5|[Обзор данных авиакомпании](https://github.com/dsibi/yandex_praktikum_da/tree/main/analytics_in_airlines)|Авиация|Предобработка данных;  исследовательский анализ данных|`Pandas` `Matplotlib` `NumPy` `re`|
|6|[Оценка источников трафика](https://github.com/dsibi/yandex_praktikum_da/tree/main/assessment_of_traffic_sources)|Интернет-сервис|Расчет экономических показателей (метрики юнит-экономики); оценка окупаемости инвестиций в маркетинг; поиск "узкого места" в экономической модели; когортный анализ|`Pandas` `Matplotlib` `NumPy` `Seaborn` |
|7|[Приоритизация гипотез и оценка результатов А/В-теста](https://github.com/dsibi/yandex_praktikum_da/tree/main/hypothesis_and_ab_testing)|Интернет-магазин|	Приоритизация гипотез по фреймворкам ICE и RICE; оценка результатов A/B-тестирования; построение графиков:  кумулятивная выручка, средний чек, конверсия по группам; расчет статистической значимости различий конверсий и средних чеков по сырым и очищенным данным |`Matplotlib` `Pandas` `Python` `Seaborn` `NumPy` `SciPy` `math`|
|8|[Рынок заведений общественного питания Москвы](https://github.com/dsibi/yandex_praktikum_da/tree/main/catering_market_research_in_moscow)|Общепит|Предобработка данных; запрос по API к Яндекс.Геокодеру; исследовательский анализ данных; подготовка презентации|`Pandas` `Seaborn` `Matplotlib` `Numpy` `re` `Requests` `io` `Яндекс.Геокодер` `API`|
|9|[Событийная аналитика мобильного приложения](https://github.com/dsibi/yandex_praktikum_da/tree/main/event_analytics_in_mobile_app)|Мобильное приложение |Описание воронки событий (от первого запуска до покупки); поиск разницы между клиентской и пользовательской сессиями; когортный анализ; сравнение конверсий в группах по принципу A/B-теста| `Pandas` `Seaborn` `Matplotlib` `plotly` `math` `NumPy` `SciPy` `warnings`|
|10|[Создание дашборда](https://github.com/dsibi/yandex_praktikum_da/tree/main/dashboard_creation)|Интернет-сервис|Создание пайплайна для получения данных из БД; проведение анализа взаимодействия пользователей сервиса с карточками; создание дашборда в Tableau Public; подготовка презентации|`Pandas` `SQLAlchemy` `Tableau`|


## Conferences
1. [`XXI конференция молодых исследователей образования  - МГПУ`](https://www.mgpu.ru/event/xxi-konferentsiya-molodyh-issledovatelej-obrazovaniya/).
2. [`Х Международной научно-практической конференции «Культура, наука, образование: проблемы и перспективы»`](https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fx-1632889500549795.link.sendsay.ru%2Fx_1632889500549795%2F77%2C%3D0tueAMiOsCAIOnHTNbRh9sg%2F106%2C560546%2C165719%2C%3FaHR0cHM6Ly9jb25mZXJlbmNlcy5zY2llbmNlL2NvbmZlcmVuY2VzL2tzZS0yMDIyLmh0bWw%2FdXRtX3NvdXJjZT1lbWFpbDEmdXRtX21lZGl1bT1zYWZzJnV0bV9jYW1wYWlnbj0x&data=05%7C01%7Csadykovaar%40mgpu.ru%7C6eb96dcb0c1c4b433c3b08da935cf480%7Cc6e90d3c9e3c403a83f86b3e5acb68f1%7C0%7C1%7C637984324693620430%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C2000%7C%7C%7C&sdata=PP5cEpXO9%2FxMGod0KsV8g1C3bnWkojL8eK8IwOudptI%3D&reserved=0), которая пройдет 10 ноября 2023 г. в очно-дистанционном формате в Нижневартовском государственном университет (г. Нижневартовск, Россия). Прием заявок и регистрация участников осуществляются в срок до 27 октября 2023 г.
3. [`13th Computer Science On-line Conference 2024`](https://csoc.openpublish.eu/). Paper Submission Deadline: December 20, 2023.
4. Рецензируемый журнал [`«Экономика: вчера, сегодня, завтра»`](http://www.publishing-vak.ru/economy.htm).
5. Рецензируемый журнал [`«Вестник МГПУ. Серия «Информатика и информатизация образования»`](https://dlt.mgpu.ru/).
6. [XXV ВСЕРОССИЙСКАЯ СТУДЕНЧЕСКАЯ НАУЧНО-ПРАКТИЧЕСКАЯ КОНФЕРЕНЦИЯ НИЖНЕВАРТОВСКОГО ГОСУДАРСТВЕННОГО УНИВЕРСИТЕТА](https://konference.nvsu.ru/konf/383)



## Summary table of literature sources
Разделы | 👨‍🏫 Курсы | 📚 Книги | 📊 Данные | 🙋‍♂️ Посты | ✊ Софт
--- | --- | --- | --- | --- | ---
Data Analyst with Python | [Data Analyst](https://github.com/elmoallistair/datacamp-data-analyst-with-python) | [Книги по Data Analyst](https://practicum.yandex.ru/blog/top-knig-po-analitike/) | + | [Источники ](books/social_data_science.md) | [Программы и библиотеки ](https://habr.com/ru/post/542718/)

