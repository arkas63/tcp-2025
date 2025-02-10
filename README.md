# Введение в лабораторные работы по курсу "Основы сетевого программирования"

## Описание курса
Курс "Основы сетевого программирования" направлен на изучение принципов построения клиент-серверных приложений, взаимодействия с базами данных и организации веб-сервисов. В рамках лабораторных работ предстоит разработать полноценное веб-приложение, состоящее из трех компонентов: серверной части, базы данных и клиентского интерфейса. Проект будет развернут в Docker-контейнерах, также необходимо использовать Git, в качестве системы контроля версий.

## Формат работы
- **Работа выполняется в парах**: необходимо заранее определиться с напарником.
- **Выбор тематики приложения**: перед началом работы необходимо выбрать тематику проекта (например, система управления задачами, трекер расходов, сервис бронирования и т. д.).
- **Использование системы контроля версий Git** (рекомендуется GitHub).
- **Работа в среде разработки VS Code** с соответствующими плагинами для Java, Python, Docker и т.д.

## Этапы выполнения лабораторных работ
### Лабораторная работа 0: Проектирование приложения
- Определение концепции приложения.
- Выбрать стек технологий.
- Создание схем базы данных и API.
- Настройка репозитория Git, добавление `.gitignore`.

### Лабораторная работа 1: Разработка базы данных
- Настройка SQLite/PostgreSQL (локально или через Docker).
- По желанию можно использовать также NoSQL БД.
- Создание моделей ORM, выполнение миграций.
- Реализация модели пользователя.
- Скрипт для подтверждения корректности работы ORM.

### Лабораторная работа 2: Разработка API
- Разработка RESTful API;
- Тестирование API с помощью Postman или `curl`.

### Лабораторная работа 3: Авторизация
- Настройка аутентификации с помощью JWT.
- Защита маршрутов API.

### Лабораторная работа 4: Разработка клиентской части
- Создание интерфейса с использованием шаблонизатора Jinja2 (для Flask/Django) или Spring Thymeleaf (для Java-приложений).
- По желанию можно использовать React.
- Настройка взаимодействие с API и обработка ошибок (кастомная страница для обработки статусов 401, 403, 404).
- Для React: настройка отправки запросов на сервер (Axios/Fetch API).

### Лабораторная работа 5: Финализация приложения и упаковка в Docker
- Интеграция клиентской и серверной частей.
- Упаковка проекта в Docker.
- Настройка `.dockerignore`.
- Создание `docker-compose.yml` для управления сервисами;
- Итоговое тестирование и подготовка отчета.

## Формат сдачи
- **Отчет** (word-документ с описанием архитектуры, кода и полученных результатов).
- **Презентация** с кратким описанием выполненной работы.
- **Git-репозиторий** с рабочим проектом.
