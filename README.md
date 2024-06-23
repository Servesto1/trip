Итоговый проект виртуальной стажировки Skillfactory

ЗАДАЧИ

 Заказ от Федерация Спортивного Туризма  России (ФСТР) разработать мобильное приложение для  Android и IOS, которое упростило бы  задачу туристам
 по отправке данных о перевале и сократило время обработки запроса до 3 дней. Пользоваться данным приложения будут туристы. В горах они будут 
 вносить данные о перевале в приложении и отправлять их в  ФСТР, как только появиться доступ в интернет. Модераторы из ФСТР будут верифицировать
 и вносить информациб в базу данных, полученную от пользователей, а те в свою очередь  смогут увидеть в мобильном приложении статус модерации
 и просматривать базу с объектами, внесенной другими пользователями.

 ОПИСАНИЕ ПРОЕКТА

 Мобильное приложение для Android и IOS, пользователями которого будут туристы. Туристы будут в горах вносить данные о перевале в приложении и 
 отправлять их в ФСТР, как только у них появиться связь информация о внесенных данных. Приложение служит для передачи информации между туристами,
 которые учавствуют или планируют поход.

 Реализованае задачи в проекте:
 - создана база данных (БД),
 - разработанны классы в БД,
 - подготовлена документация,
 - реализованы методы для REST API: POST SubmitData, GET/SubmitData/, PATCH/SubmitData/, id, GET/SubmitData/?user_email=email.

ВОЗМОЖНОСТИ ПРИЛОЖЕНИЯ

Доступные функции для пользователей:
1) Внесение в карточку  новой информации об объекте в перевале.
2) Редактирование в приложении неотправленных на сервер ФСТР данных об объекте.
3) Заполнение контактных данных (ФИО, электронная почта, номер телефона) с  последующем автозаполением.
4) Отправка данных на сервер ФСТР.
5) Получение информации об отправке на сервер ФСТР.
6) Согласие пользователя при отправки сообщения на  обработку персональных данных.

Используется передача данных заполяемых пользователем в приложении:
1) Фамилия, имя и отчество пользователя.
2) Электронная почта и номер телефона пользователя.
3) Название перевала.
4) Фотографии с перевалов.
5) Координаты  и высота перевала.

Проект размещен на хостинге pythonanywhere.com:http://____________.pythonanywhere.com/api/submitData/ 