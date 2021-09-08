# Backend дипломного проекта о фильмах Яндекс.Практикума
------
## О чём этот проект:
### Функционал
* База данных с 2умя сущностями - пользователь (user) и сохранённые фильмы (movie)
* Обработка конроллерами запросов к API
* Логирование запросов и ошибок

## База данных
## Пользователь (user)
* создается на основе схемы из 3х полей
## Сохранённые фильмы (movies)
* создается на основе схемы из 12и полей

### Роуты
### Реализована обработка 7 роутов. 2 роута доступны без авторизации
* регистрация пользователя и аутентификация пользователя
### 5 роутов доступны после получения токена jwt
* возвращение информации о пользователе, изменение информации о пользователе, возвращение всех сохраненных фильмов, создание фильма, удаление фильма по id

#### Запуск проекта
npm run start — запускает сервер
npm run dev — запускает сервер с hot-reload

## Ссылки
API сервиса - https://api.bukhgolts.nomoredomains.club
