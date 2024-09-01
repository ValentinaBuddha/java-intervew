# Календарь Бумеранг
В рамках трёхдневного хакатона, организованного компанией Неофлекс на платформе Codenrock, Командой CyberKittens в составе аналитиков, Data инженеров, тестировщиков, Java-азработчика и 
Девопс специалиста на хакатоне от компании Neoflex спроектировано и реализовано приложение 
для удобного назначения встреч рекрутёра, соискателя и эксперта.

Деплой приложения был осуществлён в кластер Kubernetes через gitlab. Здесь на github код сохранён для ознакомления. 

![Промо](/documents/киберкитенс.jpg)



### Описание
- Приложение представляет из себя календарь.
- Пользователь приложения (рекрутёр), выбрав список участников для встречи (эксперт и кандидат), получает список общих свободных слотов.
- Выбирает удобное время и назначает встречу.
- Отправляет запросы на участие во встрече и отменяет их.
- Другие участники подтверждают или отклоняют запросы.

### Схема БД
![Промо](/documents/бд.jpg)



### Стек технолoгий
Java 17, Spring boot, Hibernate, PostgreSQL, Kubernetes, Gitlab, Docker, Power BI

### Визуальное описание бизнес-процесса
![Промо](/documents/бизнес-процессы.jpg)



### Визуальное описание интерфейса
![Промо](/documents/создатьвстречу.jpg)
![Промо](/documents/лк.jpg)
![Промо](/documents/входвлк.jpg)
![Промо](/documents/регистрация.jpg)
![Промо](/documents/изменениеанных.jpg)



### Тестовые данные для базы данных
Для визуализации полученных данных было настроено подключение к Power BI и собраны примеры дашбордов.


![Промо](/documents/бд1.jpg)
![Промо](/documents/бд2.jpg)


Для анализа работы отдела были созданы витрины. Некоторые из них представлены ниже, а именно, витрина проведенных встреч, загруженности отдела по дням недели и витрина с общей информацией о собеседованиях


![Промо](/documents/бд3.jpg)
![Промо](/documents/бд4.jpg)
![Промо](/documents/бд5.jpg)



### Планы по доработке проекта
- тестирование существующего функционала
- валидация
- добавление нового функционала, например, отправка email, изменение статуса встречи, полчение свободного времени для всех дат текущего времени
- добавление liquibase
- коррекция схемы бд

