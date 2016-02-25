service: tracker
service_name: K☆50:Трекер

#Особенности коллтрекинга К50

##Типы коллтрекинга

К50:Трекер использует технологии статического (закрепление номера за источником) и динамического коллтрекинга (закрепление номера за пользователем). Также доступен уникальный тип ротации номеров, который позволит ещё больше снизить стоимость коллтрекинга для определенных задач (подробности см. ниже).
Таким образом, вы можете настроить коллтрекинг, выполняющий ваши задачи по оптимальной цене.

##Очень простое подключение

Для начала работы с коллтрекингом достаточно установить на сайт код счетчика:

```js
<script src="http://cdn.k50.ru/k50/k50tracker2.js"></script>
<script>var k50TrackerInstance = k50Tracker.init({siteId: XXXXXXX});</script>
```
Прочие настройки осуществляются непосредственно в интерфейсе трекера.
Код можно вставлять через Google Tag Manager

##Параллельная ротация номеров
Вы можете одновременно закреплять за пользователем любое число номеров. При этом все данные будут доступны в одном счетчике.

Данный функционал будет полезен клиентам с большим числом используемых номеров на сайте (например, автодилеры с несколькими дилерскими центрами).

##Гибкие условия подмены номеров
К50:Трекер позволяет подменять номера с большим спектром условий.

**Некоторые параметры, которые можно использовать в условиях подмены номера**

+ Страница входа
+ Любые get-параметры, передаваемые в странице (utm метки и пр.)
+ Источник трафика (yandex.ru, google.com и пр.)
+ Тип трафика (поисковый системы, социальные сети и пр.)
+ Регион пользователя (можно показывать пользователям из Москвы номера 495, для Спб - 812 и т.д.)
+ IP-адрес - позволяет исключить часть пользователей из ротации номеров (например, блокируем ротацию номеров для собственного офиса или для поставщиков товара)
+ Собственный параметр (например, можно настроить подмену номера на основе данных cookie пользователя)

##Ротация номеров по любым параметрам
Помимо классической ротации номеров в динамическом коллтрекинге (с закреплением номера за пользователем) К50:Трекер позволяет закреплять номера за произвольным параметром.

Данный тип ротации имеет смысл использовать, когда вам важно понимать источник трафика, но не важна информация о конкретном посещении. Использование подобного типа ротации позволяет сэкономить на числе закупаемых номеров (в том числе и для статического коллтрекинга).

**Примеры использования**

+ Оценка эффективности площадок - закрепляем номера за источниками
+ Отслеживание эффективности CPA партнеров - закрепляем номера за партнерами
+ Неглубокая оценка CPC кампаний - закрепляем номера за utm_campaign, чтобы получить статистику по звонкам на уровне кампаний

##Динамическое резервирование номера за пользователем
При использовании динамического коллтрекинга для наибольшей эффективности отслеживания номер телефона закрепляется за пользователем на весь сеанс и на определенное время после сеанса, которое зависит от качественных показателей трафика

##Анализ звонков в 3 моделях атрибуции
Вы можете просматривать статистику по звонкам в 3 моделях атрибуции атрибуции: по последнему взаимодействию, по первому взаимодействию и по линейной модели.