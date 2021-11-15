Выполненная задача:
приложение клиент-сервер простейшей рекомендательной сети. 
Стэк: ExtJs, Php, MySql

Приложение рабочее, вмеру оттестированное, выполняет следующие функции:
- Просмотр списка товаров и комментариев с оценками;
- Регистрация, авторизация, выход пользователей;
- Добавление комментариев и оценки товара (голосование), работает только для зарегистрированных пользователей;
- При входе пользователя создается примитивная сессия, храниться в куки браузера;

Что внутри:
постарался сделать аккуратную проверку внесенных данных в формах (regexp, подсветка);
на сервере пресек попытки сохранить данные без сессии, проверял обязательное наличие всех полей в каждом запросе;
JavaScript сделан в MVC стиле, Php в процедурном, по-простому; 

В БД реализованы 3 сущности Products,Ranks,Users;
Названия переменных, методов, функций говорят сами за себя, в нескольких сложных местах Javascript написал комментарии;
Дизайн рассматривал с точки зрения юзабилити, на визуал времени не хватило, в chrome на телефоне немного разъезжается.


