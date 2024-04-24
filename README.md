# Портфолио.

Здесь собрана информация (включая ссылки и статусы) обо всех проектах, которые я успешно завершил или над которыми работаю сейчас. В том числе pet-проекты, соревнования, коммерческие проекты, учебные проекты.

* В каждой категории - Сверху более новые проекты, снизу более старые.

## Pet-проекты

| Название | Задача | Данные | Описание | Статус | Инструменты |
| --- | --- | --- | --- | --- | --- |
| [**Предсказание стоимости недвижимости в Москве и Подмосковье**][10] | Создать модель машинного обучения для предсказания стоимости недвижимости в Москве и подмосковье (в частности Раменское и Жуковский) с использованием данных, полученных с помощью библиотеки Cianparser. | Парсинг открытых данных с сайта [***Циан***][9] | Среди моих знакомых и родных в последнее время часто идут разговоры о недвижимости в Москве и МО, у кого-то она есть, а кто-то планирует переезжать да и я сам хочу присмотреть что-нибудь в МО. Поэтому решил разобраться в этой теме и используя отрытые данные построить модель оценки стоимости домов и таунхаусов (позже возможно добавлю квартиры). | *В процессе* - добавление гео-данных (координаты, расстояния) | Python, pandas, numpy, cianparcer, GeoPy, PyCaret, sklearn, CatBoost, XGBoost, matplotlib, seaborn |
| [**Предсказание стоимости авто по VIN-номеру**][5] | Основной целью проекта было создание модели, способной предсказывать стоимость автомобиля с приемлемой точностью на основе информации, извлеченной из его VIN-кода. | Для обучения и тестирования модели использовался набор данных, содержащий VIN-коды автомобилей и соответствующие цены. | В данном проекте была разработана модель машинного обучения для предсказания стоимости автомобиля по его VIN-коду. VIN-код (Vehicle Identification Number) - это уникальный идентификатор транспортного средства, который содержит информацию о его производителе, модели, годе выпуска, характеристиках и других параметрах. | Завершён. (Создано веб-приложение на strimlit) | NumPy, Pandas, PyCaret, scikit-learn, Matplotlib, re, time, skimpy, chime, Pipeline, CatBoost, XGBoost, LightGBM |
| [**Предсказание успешности стартапов.**][6] | Целью данного исследования является построение модели машинного обучения, способной прогнозировать закрытие стартапов с высокой точностью. В рамках исследования будут идентифицированы ключевые факторы, влияющие на успех или провал стартапов, а также проанализирована эффективность модели на различных временных периодах и для разных категорий стартапов. | Датасет состоит из двух файлов: тренировочный набор (около 53к записей) и тестовый набор (около 13к записей). Тренировочный набор содержит целевой признак status, указывающий на то, закрылся стартап или продолжает действовать. Временной период - '1970-01-01' по '2018-01-01'. Дата формирования выгрузки - '2018-01-01' | Прогнозирование закрытия стартапов является актуальной задачей в современной экономике, где инновации и предпринимательство играют ключевую роль. Успех стартапа зависит от множества факторов, таких как финансирование, команда, продукт, рынок и внешние условия. Разработка эффективных моделей прогнозирования может помочь снизить риски инвестиций и повысить шансы на успех новых предприятий. | Завершён (Создана ML-модель, составлен [***отчёт***][7]) | pandas, numpy, skimpy, matplotlib, seaborn, sklearn, pycaret, Catboost, LightGBM, XGBoost |
| **Multi-label классификация обратной связи пользователей маркетплейса (NLP)** | Автоматизировать исследование обратной связи пользователей маркетплейса для *SAMOKAT TECH*. | Представляют собой ответы из проведенного опроса. Опросник состоял из списка закрытых вопросов с выбором одного ответа и открытого вопроса с пользовательским комментарием. Необходимо для каждого ответа из 50 различных меток классов выбрать все затронутые. | В современном мире электронной коммерции обратная связь пользователей играет решающую роль в понимании потребностей клиентов, определении областей для улучшения и принятии обоснованных бизнес-решений. Однако, анализ больших объемов отзывов вручную – это трудоемкий и неэффективный процесс. Именно здесь на помощь приходит машинное обучение и обработка естественного языка (NLP) | Завершён (Создана ML-модель) | Python, pandas, numpy, skimpy, re, pymorphy2, matplotlib, sklearn, bert, Catboost, Lightgbm. XGBoost |
| **Предсказание повторных покупок клиентов** | Разработать модель машинного обучения, способную предсказывать, совершит ли клиент повторную покупку в течение ближайших 30 дней. | Проект использует данные о истории покупок клиентов из трех магазинов. | Эта модель может быть использована для оптимизации маркетинговых кампаний и повышения лояльности клиентов. | Завершён (редактирование финальных выводов) | Python, pandas, numpy, scikit-learn, PyCaret, CatBoost, LightGBM |
| **Разработка торговой системы** | Разработка собственной торговой системы для срочного рынка Московской биржи. Проект демонстрирует навыки в области анализа данных, финансового моделирования и алгоритмической торговли.| Данные о котировках активов экспортированные с [*finanm.ru*][11] | **Результат:** Успешное применение разработанной торговой системы на срочном рынке Московской биржи. Доходность системы превышает доходность основных индексов, таких как S&P 500 и IMOEX, а также доходность безрисковых инвестиций, таких как ОФЗ. Этот проект не только показывает умение применять Data Science на практике, но и значительно расширяет мои опыт в области финансового анализа и трейдинга. | **Завершён и в эксплуатации** - выработаная стратегия применяется с февраля 2024г. [**В процессе**][13] - создание публичного репозитория для открытого использования | Python, pandas, matplotlib, seaborn, pycaret, optuna, joblib, pandas_ta, yf_finance, telebot, bootstrap, math, scipy, Технический Анализ |
| [**Прогнозирование стоимости автомобилей на вторичном рынке**][12] | Разработать модель машинного обучения для прогнозирования стоимости автомобилей на основе характеристик автомобиля и рыночных данных. Исследовать зависимость стоимости автомобиля от различных характеристик и построить модель для определения стоимости автомобиля с высоким качеством предсказания.| Файлы в формате `.csv` с данными о продаваемых машинах | Получилась модель на основе Catboost с высокой точностью предсказания - метрика `MAPE` `0.13`| Завершён (Создана ML-модель) | Python, pandas, numpy, skimpy, matplotlib, seaborn, sklearn, Optuna, Catboost |


## Cоревнования
  
| Название | Источник | Задача | Описание | Статус | Инструменты |
| --- | --- | --- | --- | --- | --- |
| [**Анализ и визуализация целей обучения студентов “Яндекс Практикум”**][1] | Яндекс Практикум | Создание и оформление отчёта целей обучения студентов Яндекс Практикума для презентации топ-менеджменту Яндекс Практикума | Участвовал на соревнованиях в команде из 8 человек (4 аналитика (включая меня), 3 дизайнера и 1 Project Manager), основной задачей для меня было - создание кластеризации с помощью метода kmeans, а так же формулировка гипотез и оформление выводов. | Завершён. | Python, Pandas, Numpy, kmeans, plotly |

## Учебные проекты

| Название курса | Школа | Описание | Статус | Инструменты | Ссылка на репозиторий |
| --- | --- | --- | --- | --- | --- |
| [**Специалист по Data Science**][2] | [Яндекс Практикум][3] | **15 Проектных работ**, которые я сделал во время прохождения курса "Специалист по Data Science" в Яндекс.Практикум.  | Завершён. | Python, ML, NLP, CV, DL, Статистический анализ, Теория вероятностей, Анализ данных| [Github][4] |

[1]:https://github.com/FedorSafonov/Projects/tree/main/Hackatons_and_competition/Yandex_Practicum_hackaton
[2]:https://practicum.yandex.ru/data-scientist/
[3]:https://practicum.yandex.ru/
[4]:https://github.com/FedorSafonov/Projects/tree/main/yandex_praktikum_projects%20(Data_Science)
[5]:https://github.com/FedorSafonov/Predicting-the-cost-of-a-car-by-VIN-code
[6]:https://github.com/FedorSafonov/Predicting-the-success-of-startups/tree/main
[7]:https://github.com/FedorSafonov/Predicting-the-success-of-startups/blob/main/Report.MD
[8]:https://github.com/FedorSafonov/Predicting-the-value-of-real-estate-in-the-Moscow-region
[9]:https://cian.ru
[10]:https://github.com/FedorSafonov/Predicting-the-value-of-real-estate-in-the-Moscow-region
[11]:https://www.finam.ru/quote/batsnq/qqq/export/
[12]:https://github.com/FedorSafonov/Projects/tree/main/Hackatons_and_competition/Kaggle/used_cars_price_prediction
[13]:https://github.com/FedorSafonov/Trading-algorithms-based-on-machine-learning
