# TaxoBus
TaxoBus is same about as BlaBlaCar

Техническое задание на разработку сервиса заказа такси вскладчину из Велтонпарка до Мега(Химки).

1. Сайт сервиса http://localhost:8080/TaxoBus:
2. На главной странице:
2.1. Список анонсов доступных поездок. В анонсе отображается время поездки, текущее количество пассажиров, общая стоимость и стоимость для одного пассажира. Пассажиров может быть не больше 4. При нажатии на кнопку инфо открывается страница с информацией о поездке: время отправления, количество пассажиров, ФИО(логин?) и контактный телефон каждого пассажира, указанный при регистрации; ФИО(Логин?)+фото водителя, его контактный телефон, указанный при регистрации, автомобиль, номер автомобиля, общая стоимость поездки, стоимость для одного пассажира, форма для пожеланий/комментариев, чат поездки(?). 
2.2. Маршрут с указанием места отправления(+вставка изображения с Yandex Карты) и прибытия. В дальнешем при добавлении новых маршрутов по маршруту можно фильтровать поездки.
3. Авторизованные пользователи с ролью "PASSENGER" могут создавать свои поездки. Кнопка добавления на панели меню.
4. Авторизованные пользователи с ролью "PASSENGER" могут изменять свои поездки. Кнопка "Изменить" под анонсом и под поездкой.
5. Авторизованные пользователи с ролью "PASSENGER" могут удалять свои поездки. Кнопка "удалить" под самой поездкой. Удалять поедку можно только, если никто кроме создателя не присоеденился к поездке.
6. Авторизованные пользователи с ролью "PASSENGER" могут завершать свои поездки. Кнопка "Завершить" под самой поездкой.
7. Авторизованные пользователи с ролью "PASSENGER" могут присоединяться к доступным на главной странице поездкам. Для этого необходимо нажать кнопку "Я с вами!". Кнопка "Я с Вами!" под анонсом поездки и под самой поездкой. При нажатии на данную кнопку открывается форма(возможно ли сделать форму?)/страница, где указывается количество добавляемых пассажиров. На данной странице находится кнопка "Подтвердить". При нажатии на неё происходит добавление пассажиров к поездке и возврат на обновлённую страницу поездки.
8. Авторизованные пользователи с ролью "DRIVER" могут создавать свои поездки. Кнопка добавления на панели меню.
9. Авторизованные пользователи с ролью "DRIVER" могут изменять свои поездки. Кнопка "Изменить" под анонсом и под поездкой.
10. Авторизованные пользователи с ролью "DRIVER" могут удалять поездки. Кнопка "удалить" под самой поездкой.
11. Авторизованные пользователи с ролью "DRIVER" могут завершать поездки. Кнопка "завершить" под самой поездкой.
12. Авторизованные пользователи с ролью "ADMIN" могут регистрировать и удалять новых пользователей с ролями "PASSENGER" и "DRIVER". При регистрации указывается ФИО и контактный телефон пользователя.
13. Любая страницы должна иметь панель меню вверху, на которой есть пункты меню
-- "Поездки" - отображается для всех пользователей. Отображает список анонсов поездок.
-- "Добавить поездку" - отображается для авторизованных пользователей.
-- "Войти" - отображается для не аутентифицированных пользователей
-- "Выйти" - отображается для аутентифицированных пользователей
