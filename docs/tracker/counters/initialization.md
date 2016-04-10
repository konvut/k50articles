service: tracker
service_name: K☆50:Трекер
last_modified: 2016-03-09

#Инициализация счетчика

JavaScript-библиотека, отвечающая за работу счётчика загружается с URL http://cdn.k50.ru/k50/k50tracker2.js (https://k50-a.akamaihd.net/k50/k50tracker2.js - для https сайтов).
Код для подключения библиотеки доступен на странице редактирования счётчика. Библиотека может быть загружена асинхронным и синхронным способом, однако, её функционал при этом остаётся неизменным.

##Пример для HTTP сайта

```js
<script src="http://cdn.k50.ru/k50/k50tracker2.js"></script>
<script>var k50TrackerInstance = k50Tracker.init({siteId: 123456789});</script>
```

##Пример для HTTPS сайта

```js
<script src="https://k50-a.akamaihd.net/k50/k50tracker2.js"></script>
<script>var k50TrackerInstance = k50Tracker.init({siteId: 123456789});</script>
```