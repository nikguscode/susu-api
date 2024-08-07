# susu-api (в разработке)

# RU 
<details>
<summary>Кликните, чтобы развернуть</summary>

## Описание API
Данное API создано для взаимодействия с сервисами ЮУрГУ, среди которых: studlk.susu.ru, edu.susu.ru, online.susu.ru. API доступно для взаимодействия только студентам ЮУрГУ, **пароли от учётных записях не собираются, не хранятся и не передаются.**
Интерфейс состоит только из POST запросов, так как для взаимодействия с сервисами ЮУрГУ необходимо пройти аутентификацию.

## Функции
* Куки сессии: `POST/susu-api/authentication`
* Итоговые оценки: `POST/susu-api/grades`
* Процентная успеваемость: `POST/susu-api/percentage`
* Учебный план: `POST/susu-api/study-plan`
* Рабочая программа дисциплины (РПД): `POST/susu-api/rpd`
* Расписание: `POST/susu-api/schedule`
* Читательский билет: `POST/susu-api/library-card`
* Пропуск: `POST/susu-api/badge`

</details>
