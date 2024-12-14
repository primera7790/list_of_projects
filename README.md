# Список проектов

<br>

## **Pet-проекты**

### [**ZAVOD_project**](https://github.com/primera7790/ZAVOD_project/tree/master/zavod)
  
**Технологии:**
- Язык: &nbsp; `python` ;
- Библиотеки: &nbsp; `pandas` , `numpy` , `sklearn` , `matplotlib` ;
- ML-алгоритмы: &nbsp; `kNN` , `Decision Tree` .

**Описание:** <br>

&nbsp; &nbsp; Программа преобразует множество excel-файлов (с вручную записанными данными) в единую csv-таблицу. <br>
&nbsp; &nbsp; Подготовливает данные (извлекает, нормирует, обеспечевает достаточность). <br>
&nbsp; &nbsp; На основе полученных данных производится их агрегация, аналитика и визуализация.

**Основные процессы:**
- сбор данных;
- обработка;
- структурирование;
- классифицирование по наибольшему подобию, применяя метод ___kNN___;
- перевод определенных данных в признаковое пространство и дальнейшая классификация при помощи ___Decision Tree___ модели;
- агрегация, аналитика и визуализация (формирование презентации).

<br>

### [**Trading_assistant**](https://github.com/primera7790/Trading_assistant)

**Технологии:**
- Язык: &nbsp; `python` ;
- Фреймворки: &nbsp; `django` ;
- Сайт: &nbsp; `html` , `css` ;
- Парсинг: &nbsp; `requests` , `bs4` , `lxml` , `selenium` ;
- База данных: &nbsp; `sqlite3` ;
- Телеграм-бот: &nbsp; `aiogram` ;
- Автоматизация: &nbsp; `asyncio` , `apscheduler` , `celery` , `rabbitmq` , `docker` .
    
**Описание:** <br>
  
&nbsp; &nbsp; __Задача:__ &nbsp; Снижение психологической нагрузки на трейдера во время биржевой торговли. <br>
&nbsp; &nbsp; __Решение:__ &nbsp; Математически обоснованное регулирование объемов сделок и исключение необоснованного риска. При необходимости - ограничение торговли. <br>
&nbsp; &nbsp; __Преимущества:__ &nbsp; Трейдер изолирован от информации о промежуточном финансовом результате, что позволяет не думать о состоянии баланса, а сконцентрироваться на сделке.

<br>  

## **Освоение технологий**

### **PyTorch + FastAPI + Docker <br> [Pytorch regression problem](https://github.com/primera7790/pytorch_regression)**

**Технологии:**
- Язык: &nbsp; `python` ;
- Фреймворки: &nbsp; `pytorch`, `fastapi` ;
- Библиотеки: &nbsp; `numpy`, `yaml` , `matplotlib` ;
- Frontend: &nbsp; `html`, `jinja` ;
- ML-алгоритмы: &nbsp; `ModelReg` .
  
**Описание:** 

&nbsp; &nbsp; **Задача:** &nbsp; Определение координат центра случайно расположенной фигуры (квадрата внутри квадрата); <br>
&nbsp; &nbsp; **Данные:** &nbsp; При помощи numpy генерируем случайный набор данных в uint8. <br>
Используем pillow для сохранения полученных матриц в виде изображений. <br>
Прописываем собственный класс формирования датасета; <br>
&nbsp; &nbsp; **Модель:** &nbsp; Пишем класс полносвязной нейронной сети; <br>
&nbsp; &nbsp; **Функции активации:** &nbsp; ReLU; <br>
&nbsp; &nbsp; **Функция потерь:** &nbsp; MSELoss; <br>
&nbsp; &nbsp; **Конечный вид:** &nbsp; Пишем элементарную html-страничку. <br>
На fastapi прописываем backend часть и присоединяем frontend. <br>
Формируем docker-образ, разворачиваем контейнер, поднимаем локальный сервер.

<br>

### **MLflow + Airflow <br> [Linux or Windows from?](https://github.com/primera7790/linux_or_windows)**

**Технологии:**
- Язык: &nbsp; `python` ;
- Фреймворки: &nbsp; `mlflow`, `airflow` ;
- Библиотеки: &nbsp; `sklearn`, `pyyoutube` , `yaml` , `numpy` , `pandas` , `nltk`, `pymystem3` ;
- ML-алгоритмы: &nbsp; `LogisticRegression` , `RandomForestClassifier` .
  
**Описание:** <br>

&nbsp; &nbsp; Предсказание тематики видео, под которым оставлен комментарий (Linux или Windows). <br>
&nbsp; &nbsp; Трекинг и логирование модели реализованы при помощи ***MLflow***.<br>
&nbsp; &nbsp; За регулярность переобучения отвечает ***Airflow***.

<br>

## **Соревнования**

### Kaggle.com <br> [**House Prices - Advanced Regression Techniques**](https://github.com/primera7790/Kaggle.com/tree/master/House%20Prices%20-%20Advanced%20Regression%20Techniques)

**Технологии:**
- Язык: &nbsp; `python`;
- Библиотеки: &nbsp; `pandas`, `numpy`, `sklearn`, `matplotlib`, `optuna`;
- Алгоритмы: &nbsp; `XGBoost`.

**Описание на Kaggle.сom:** <br>

&nbsp; &nbsp; [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)<br>
&nbsp; &nbsp; Score: 0.12933 (Root Mean Squared Logarithmic Error). <br>
&nbsp; &nbsp; Among the top 21-25%.

<br>

### GPN INTELLIGENCE CUP <br> [**Data Scientist в разработке инновационных решений**](https://github.com/primera7790/GPN-INTELLIGENCE-CUP/tree/master/Data%20Scientist%20%D0%B2%20%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B5%20%D0%B8%D0%BD%D0%BD%D0%BE%D0%B2%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D1%85%20%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B9)

**Технологии:**
- Язык: &nbsp; `python`;
- Библиотеки: &nbsp; `pandas`,  `sklearn`, `matplotlib`, `seaborn`;
- Алгоритмы: &nbsp; `XGBoost`, `LinearRegression`, `DecisionTreeRegressor`, `RandomForestRegressor`, `AdaBoostRegressor`, `SVR`.

**Описание:** <br>

&nbsp; &nbsp; Задача на построение модели регрессии с обязательной предобработкой данных.

<br>

## **Практические задачи**

### [**Neural_network_on_python**](https://github.com/primera7790/Neural_network_on_python)
&nbsp; &nbsp; Поставил сам себе задачу реализовать вручную каждый из этапов работы полносвязной нейронной сети. <br>
&nbsp; &nbsp; Значительно улучшил понимание внутренних процессов. <br>
&nbsp; &nbsp; Структурировал как знания, так и все последовательности внутри класса.

**Технологии:**
- Язык: &nbsp; `python` ;
- Библиотеки: &nbsp; `numpy` , `matplotlib` ;
- Датасеты: &nbsp; `MNIST (pytorch)` .

**Описание:** <br>
  
&nbsp; &nbsp; Полносвязная нейронная сеть, написанная с нуля, исключительно на связке python + numpy. <br>
&nbsp; &nbsp; **Задача:** &nbsp; Распознавание (классификация) рукописных цифр; <br>
&nbsp; &nbsp; **Данные:** &nbsp; Датасет MNIST из библиотеки torchvision, PyTorch; <br>
&nbsp; &nbsp; **Функции активации:** &nbsp; ReLU; <br>
&nbsp; &nbsp; **Функция потерь:** &nbsp; softmax + cross-entropy.

<br>

### [**ML_training_Yandex**](https://github.com/primera7790/ML_training_Yandex)
&nbsp; &nbsp; Решенные задачи: 9/9. <br>
&nbsp; &nbsp; Углубился в линейную алгебру. Начал видеть данные матрицами и векторами. <br>
&nbsp; &nbsp; Повысил эффективность своего кода.

**Технологии:**
- Язык: &nbsp; `python` ;
- Среда выполнения: &nbsp; `jupiter notebook` , `google colab` ;
- Библиотеки: &nbsp; `numpy`, `sklearn` , `matplotlib`, `scipy` , `pytorch` , `shap` ;
- Датасеты: &nbsp; `DESCR (sklearn)` , `MNIST (pytorch)` .
  
**Описание:** <br>
  
&nbsp; &nbsp; Решенеие практических задач по ML. Ручная реализации методов и подходов, используемых в ML: <br>
&nbsp; &nbsp; &nbsp; - &nbsp; метод k-ближайших соседей; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; распределение Лапласа; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; производные для уравнений линейной регрессии; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; степенной метод, алгоритм поиска собственных векторов матриц и собственных значений; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; метод Bootstrap aggregating и способ оценки Out-of-bag score; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; алгоритм бустинга; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; простая нейронная сеть на PyTorch, Deep learning; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; оценка значимости признаков модели.

<br>

### [**Algo-3.0-Yandex**](https://github.com/primera7790/Algo-3.0-Yandex)
&nbsp; &nbsp; Решено задач: 24. <br>
&nbsp; &nbsp; Познакомился с понятием асимптотической сложности алгоритмов. <br>
&nbsp; &nbsp; Выработал привычку оптимизировать собственный код при написании.

**Технологии:** <br> &nbsp; &nbsp; `python` 
   
**Описание:** <br>
  
&nbsp; &nbsp; Решение алгоритмических задач, затрагивающих: <br>
&nbsp; &nbsp; &nbsp; - &nbsp; стеки (6 задач); <br>
&nbsp; &nbsp; &nbsp; - &nbsp; очереди, деки и приоритетные очереди (5 задач); <br>
&nbsp; &nbsp; &nbsp; - &nbsp; динамическое программирование с одним параметром (4 задачи); <br>
&nbsp; &nbsp; &nbsp; - &nbsp; динамическое программирование с двумя параметрами (2 задачи); <br>
&nbsp; &nbsp; &nbsp; - &nbsp; обход графов в глубину (5 задач); <br>
&nbsp; &nbsp; &nbsp; - &nbsp; обход графов в ширину (2 задачи). <br>
&nbsp; &nbsp; Основная цель - написание эффективного кода.

<br>
  
## **Закрепление знаний**

### [**Django_store_edu**](https://github.com/primera7790/Django_store_edu)
  
**Технологии:**
- Язык: &nbsp; `python` ;
- Фреймворки: &nbsp; `django` ;
- Сайт: &nbsp; `html` , `css` , `javascript` ;
- База данных: &nbsp; `sqlite3` ;
- Библиотеки: &nbsp; `pillow` ;
- Хостинг: &nbsp; `pythonanywhere` .

**Описание:** <br>
  
&nbsp; &nbsp; Интернет-магазин одежды. <br> 
&nbsp; &nbsp; Структура: <br>
&nbsp; &nbsp; &nbsp; - &nbsp; каталог с товарами по категориям; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; личный кабинет; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; корзина; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; окно регистрации; <br>
&nbsp; &nbsp; &nbsp; - &nbsp; окно авторизации.

**Сайт**: <br>

&nbsp; &nbsp; https://primera3472.pythonanywhere.com/

<br>
      
### [**Roman_project + wow_project (html, css only)**](https://github.com/primera7790/Roman_project_html_css_only)

**Технологии:**
- HTML5;
- CSS3.
      
**Описание:** <br>

&nbsp; &nbsp; Roman_project - шуточная страничка про друга.. для друга. Практиковался писать несложные страницы. <br>
&nbsp; &nbsp; wow_project - страничка-тест на том же скелете. А насколько хорошо Вы знакомы с классами в World of Warcraft? Задача - определить класс по сленговому названию.

**Ссылки для ознакомления:** <br>

&nbsp; &nbsp; Roman_project: &nbsp; https://primera7790.github.io/Roman_project_html_css_only/ <br>
&nbsp; &nbsp; wow_project: &nbsp; https://primera7790.github.io/Roman_project_html_css_only/wow_project/

<br>

### [**health_diet_parser**](https://github.com/primera7790/health_diet_parser)

**Технологии:**
- Язык: &nbsp; `python` ;
- Библиотеки: &nbsp; `beautifulsoup4` , `requests` , `lxml` .

**Описание:** <br>
  
&nbsp; &nbsp; Парсинг информации о БЖУ с сайта полезного питания. <br>
&nbsp; &nbsp; Программа собирает данные с сайта о различных продуктах и блюдах. <br>
&nbsp; &nbsp; Формирует csv-таблицы по категориям. Для каждой позиции указывается содержание белков, жиров, углеводов и общую калорийность.

<br>

### [**amalgama_lab_parser**](https://github.com/primera7790/amalgama_lab_parser)

**Технологии:**
  - Язык программирования: &nbsp; `python` ;
  - Основные библиотеки: &nbsp; `beautifulsoup4` , `requests` , `lxml` , `urllib3` .

**Описание:** <br>
  
  &nbsp; &nbsp; Парсинг текста песен с построчным переводом. <br>
  &nbsp; &nbsp; Указываем URL ссылку на страницу с интересующей композицией на сайте amalgama-lab.com. <br>
  &nbsp; &nbsp; Программа формирует csv-файл таким образом, что после каждой строчки на иностранном языке следует та же строчка на русском. <br>

<br>

### [**Trading_assist_bot**](https://github.com/primera7790/Trading_assist_bot)

**Технологии:**
  - Язык программирования: &nbsp; `python` ;
  - Парсинг: &nbsp; `requests` , `bs4` , `lxml` , `selenium` ;
  - База данных: &nbsp; `sqlite3` ;
  - Телеграм-бот: &nbsp; `aiogram` ;
  - Автоматизация: &nbsp; `asyncio` , `apscheduler` .

**Описание:** <br>
  
  &nbsp; &nbsp; Часть проекта [Trading_assistant](https://github.com/primera7790/Trading_assistant), реализованная через Телеграм-бота. <br>
  &nbsp; &nbsp; Запускаем, начинается поиск информации о новой сделке. В случае обнаружения, данные прогоняются через алгоритм. <br>
  &nbsp; &nbsp; Мы получаем актуальную величину следующей сделки, либо требование прекращения торговли на этот день.

<br>

### [**Owl_Telegram_bot**](https://github.com/primera7790/Owl_Telegram_bot)

**Технологии:**
  - Язык программирования: &nbsp; `python` ;
  - Основные библиотеки: &nbsp; `pyTelegramBotAPI` .

**Описание:** <br>
  
  &nbsp; &nbsp; Сомневаешься? Спроси у бота!. <br>
  &nbsp; &nbsp; Даёт случайный ответ на закрытый вопрос. <br>
  &nbsp; &nbsp; Немногословный товарищ, всегда поможет советом.. это же явно интересней подброшенной монетки!

**Ссылка:** <br>

  &nbsp; &nbsp; https://t.me/owl_companion_bot

<br>

### [**Sticker_converter_bot**](https://github.com/primera7790/Sticker_converter_bot)

**Технологии:**
  - Язык программирования: &nbsp; `python` ;
  - Основные библиотеки: &nbsp; `pyTelegramBotAPI` , `pillow` .

**Описание:** <br>
  
  &nbsp; &nbsp; Отсылаешь стикер.<br>
  &nbsp; &nbsp; Получаешь его же в .png формате.<br>
  &nbsp; &nbsp; Бот, сумевший найти свое призвание в этом мире. И ни действия более.

**Ссылка:** <br>

  &nbsp; &nbsp; https://t.me/sticker_to_pdf_bot
