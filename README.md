#Хакатон MIPT: Учебная задача

##Бриф: Создать нейронную сеть, способную генерировать текстовые отзывы о различных местах на основе определенных входных параметров, таких как категория места, средний рейтинг и ключевые слова.


##Генератор отзывов на Streamlit

## Описание

Данный проект представляет собой веб-приложение, созданное с использованием фреймворка Streamlit и модели Hugging Face. Приложение позволяет пользователям вводить данные о месте, его категории, рейтинге и ключевых словах, а затем генерировать несколько вариантов отзывов с помощью модели.

## Особенности

- **Интуитивно понятный интерфейс**: Легкость в использовании благодаря Streamlit.
- **Поддержка моделей Hugging Face**: Используется предобученная модель для генерации текста.
- **Кастомизация ввода**: Пользователь задает категорию места, средний рейтинг и ключевые слова для создания отзывов.
- **Генерация нескольких отзывов**: Возможность получить сразу несколько уникальных вариантов текста.

## Установка и запуск

### 1. Клонирование репозитория

Склонируйте данный репозиторий с GitHub:

```bash
git clone https://github.com/eduardantonoff/fine_tuning
cd fine_tuning/streamlit_app
```

### 2. Установка зависимостей

Убедитесь, что у вас установлен Python 3.7 или выше. Затем установите зависимости:

```bash
pip install -r requirements.txt
```

### 3. Запуск приложения

Запустите приложение командой:

```bash
streamlit run app.py
```

После запуска приложение будет доступно в вашем браузере по адресу:

[http://localhost:8501](http://localhost:8501)

## Использование

1. Выберите категорию места: Например, "Ресторан" или "Отель".
2. Укажите средний рейтинг: Выберите один из вариантов: "Отрицательный", "Нейтральный", "Положительный".
3. Введите ключевые слова: Например, "вкусная еда, уютная атмосфера".
4. Нажмите кнопку "Сгенерировать отзывы", чтобы получить несколько вариантов текстов.


## Пример работы

**Входные данные**
- **Категория**: Ресторан
- **Рейтинг**: Положительный
- **Ключевые слова**: "вкусная еда, уютная атмосфера"

**Сгенерированные отзывы**
- "Это было потрясающее место с вкусной едой и уютной атмосферой! Обязательно вернусь снова."
- "Ресторан приятно удивил: еда на высшем уровне, а атмосфера делает вечер незабываемым."
- "Отличное место! Всё, от еды до сервиса, было просто великолепным."

## Требования

- Python 3.7+
- Установленные зависимости из `requirements.txt`

## Поддержка

Если у вас возникли вопросы или проблемы, пожалуйста, создайте issue в репозитории или свяжитесь со мной напрямую через GitHub.

## Лицензия

Этот проект распространяется под лицензией MIT. Подробнее смотрите в файле LICENSE (если применимо).

## Благодарности

- **Streamlit** — за удобный фреймворк для создания веб-приложений.
- **Hugging Face** — за мощные модели машинного обучения.

streamlit run app.py
После запуска приложение будет доступно в вашем браузере по адресу:

http://localhost:8501
Использование
Выберите категорию места: Например, "Ресторан" или "Отель".
Укажите средний рейтинг: Выберите один из вариантов: "Отрицательный", "Нейтральный", "Положительный".
Введите ключевые слова: Например, "вкусная еда, уютная атмосфера".
Нажмите кнопку "Сгенерировать отзывы", чтобы получить несколько вариантов текстов.
Структура проекта
streamlit_app/
├── app.py               # Основной файл приложения
├── requirements.txt     # Файл с зависимостями проекта
└── README.md            # Документация проекта
Пример работы
Входные данные
Категория: Ресторан
Рейтинг: Положительный
Ключевые слова: "вкусная еда, уютная атмосфера"
Сгенерированные отзывы
"Это было потрясающее место с вкусной едой и уютной атмосферой! Обязательно вернусь снова."
"Ресторан приятно удивил: еда на высшем уровне, а атмосфера делает вечер незабываемым."
"Отличное место! Всё, от еды до сервиса, было просто великолепным."
Требования
Python 3.7+
Установленные зависимости из requirements.txt
Поддержка
Если у вас возникли вопросы или проблемы, пожалуйста, создайте issue в репозитории или свяжитесь со мной напрямую через GitHub.

Лицензия
Этот проект распространяется под лицензией MIT. Подробнее смотрите в файле LICENSE (если применимо).

Благодарности
Streamlit — за удобный фреймворк для создания веб-приложений.
Hugging Face — за мощные модели машинного обучения.
