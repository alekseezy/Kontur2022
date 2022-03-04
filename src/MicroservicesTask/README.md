# Приют котиков #
## Задание ##
Вы попали в команду, занимающуюся разработкой сервиса для приюта котиков. Команда решила использовать микросервисную архитектуру и реализовала часть сервисов:

Сервис авторизации — авторизует пользователя;
Биллинг — сервис учёта продуктов, хранит котиков, находящихся в приюте;
Биржа котиков — возвращает биржевую цену котиков разных пород;
Энциклопедия котиков — возвращает информацию о котиках разных пород.
Используя эти микросервисы, реализуйте сервис приюта котиков. Он должен уметь возвращать котиков, хранить избранных котиков, отдавать счёт на оплату котика.

Дополнительная информация:
- У интерфейсов всех сервисов, в том числе вашего, присутствуют XML теги с документацией, пользуйтесь ими;
- Кроме сервисов, вам доступна база данных. Храните в ней данные, не принадлежащие другим сервисам;
- Запросы к сервисам необходимо делать в порядке, обеспечивающем консистентность запроса. Например, если котик не добавился в биллинг, ваш сервис не должен его возвращать;
- Если сервис вернул сетевую ошибку, попробуйте отправить запрос ещё раз.