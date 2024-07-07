# Дипломный проект по профессии «Веб-разработчик»
## Сайт для онлайн бронирования билетов в кинотеатр
***
## Решенные задачи
* Разработан сайт бронирования билетов онлайн.
* Результат работы содержится в данном git-репозитории.

### Исходные данные
* [Вёрстка](https://github.com/netology-code/fs-2-diplom/blob/master/sources/layouts.zip).

## Сущности

1. **Кинозал**. Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал — прямоугольное помещение, состоит из N х M различных зрительских мест.
2. **Зрительское место**. Место в кинозале. Есть два вида: VIP и обычное. 
3. **Фильм**. Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.
4. **Сеанс**. Временной промежуток, во время которого в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.
5. **Билет**. QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс. Билет действителен строго на свой сеанс.

## Роль пользователя
* Гость — неавторизованный посетитель сайта.

### Возможности гостя
* Просмотр расписания.
* Просмотр списка фильмов.
* Выбор места в кинозале.
* Бронирование билета на конкретную дату.

## Реализация проекта
* Проект реализован в виде SPA + API.

## Технологии, использованные в проекте
* React - JavaScript-библиотека для создания пользовательских интерфейсов
* Redux/React-Redux/Thunk/RTK - библиотеки для работы с глобальным состоянием приложения

## Инструкция по запуску проекта
1. Клонируйте репозиторий: 
`git clone https://github.com/Antis85/cinema-client.git`
2. Перейдите в каталог проекта: `cd cinema-client`
3. Установите зависимости: `yarn install`
4. Запустите приложение: `yarn start`
