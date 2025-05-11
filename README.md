<h1 align="center">Добро пожаловать в мой профиль</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Меня зовут <a href="https://career.habr.com/kirshumir" target="_blank">Кирилл</a>.</h3>
<h4 align="center">С 2023 года активно занимаюсь разработкой на Java. Ниже на странице Вы можете ознакомиться с моими проектами.</h4>

### **Реализованные проекты:**

### 1. [Сервис поиска событий (афиша-событий)](https://github.com/kirshumir01/java-explore-with-me)

**Описание:** Микросервисное приложение на Spring Boot с базой данных PostgreSQL для хранения информации о мероприятиях, размещённых зарегистрированными пользователями. Приложение состоит из двух модулей: основного и модуля статистики. API разделён на три части — публичную, закрытую и административную. Для маппинга Java-объектов и взаимодействия с базой данных используется ORM-фреймворк Hibernate. Тестирование API выполнено с использованием Postman.

**Особенности:** в проекте релизован пользовательский метод в SliceableRepository для постраничной выборки данных без выполнения запроса на подсчёт общего количества записей (COUNT(*)), что снижает нагрузку на базу данных и повышает производительность при работе с большими объёмами данных.

**Функционал:**
- _**публичный API:**_ поиск мероприятий по фильтрам и подборкам, сортировка по количеству просмотров или дате, просмотр комментариев;
- _**закрытый API:**_ создание и редактирование мероприятий авторизованными пользователями, обработка заявок на участие, добавление комментариев к посещённым событиям;
- _**административный API:**_ модерация и публикация мероприятий, создание подборок, распределение категорий, управление пользователями, модерация комментариев.

![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### 2. [Сервис поиска и аренды вещей](https://github.com/kirshumir01/java-shareit)

**Описание:** Микросервисное приложение на Spring Boot с базой данных PostgreSQL для хранения и управления информацией о вещах, размещённых пользователями. Приложение разделено на два модуля: основной, реализующий бизнес-логику, и вспомогательный — для фильтрации входящих запросов пользователей. Для маппинга Java-объектов и взаимодействия с базой данных используется ORM-фреймворк Hibernate.

**Особенности:** Код покрыт мок- и юнит-тестами на 80%, что позволило существенно снизить количество ошибок по сравнению с начальной версией приложения.

**Функционал:** Размещение и управление объявлениями о вещах, регистрация и обработка заявок на аренду, отслеживание истории аренды, поиск, пользовательские отзывы.

![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### 3. [Сервис хранения фильмов и поиска друзей](https://github.com/kirshumir01/java-filmorate)

**Описание:** Приложение на Spring Boot с базой данных H2 для хранения и управления информацией о фильмах. Доступ к данным реализован с использованием Spring JDBC. Код покрыт модульными unit-тестами.

**Особенности:** SQL-запросы оптимизированы с учётом проблемы N+1 для повышения производительности.

**Функционал:** Хранение и управление данными о фильмах и пользователях, поддержка социального взаимодействия (дружба, лайки), отзывы пользователей, система оценок и рейтингов фильмов.

![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

## Прочие репозитории:

### 1. [Приложение на Java для сохранения задач и отслеживания их выполнения](https://github.com/kirshumir01/java-kanban)
### 2. [Приложение на Java для подсчета пройденных шагов и сожженных калорий](https://github.com/kirshumir01/steps-tracker)
### 3. [Приложение на Java для считывания и анализа бухгалтерских отчетов](https://github.com/kirshumir01/accounting-reports)
### 4. [Решения задач LeetCode на Java](https://github.com/kirshumir01/leetcode)
### 5. [Решения задач по SQL (sql-ex.ru)](https://github.com/kirshumir01/sql-ex)

## Моя статистика на [LeetCode](https://leetcode.com):

![Leetcode Stats](https://leetcard.jacoblin.cool/kirshumir?theme=dark&font=Rokkitt&ext=heatmap)
