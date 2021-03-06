service: tracker-api
service_name: API K☆50:Трекера
last_modified: 2016-03-09

##Получение списка счетчиков

Данный метод возвращает список доступных счетчиков. По идентификатору счетчика можно выгрузить подробную информацию о [звонках](get-calls-stat) и [заказах](get-orders-stat) 


###Синтаксис запроса

>GET http://api.tracker.k50.ru/api/me

###Пример запроса

>GET http://api.tracker.k50.ru/api/me?apiKey=**ae162273-8a98-459d-abb0-3454d0470b70**

###Формат ответа

```json
{"projects": ▿[
    {
      "name": <string>,
      "display_name": <string>,
      "counters": [
        {
          "counter_id": <string>,
          "url": <string>
        }
      ]
    },
    ...
    ]
}    
```

**Объект counterInfo**

|Параметры|Описание|
|---------|--------|
|projects|Список доступных проектов. Информация по каждому проекту передаётся в виде объекта **projectInfo**|


**Объект projectInfo**

|Параметры|Описание|
|---------|--------|
|name|Наименование инстанса проекта. Его также можно увидеть в ссылке трекера - **name**.tracker.k50.ru|
|display_name|Отображаемое название проекта|
|counters|Счетчиков, созданных в проекте. Информация по каждому счетчику передаётся в виде объекта **counterInfo**|


**Объект counterInfo**

|Параметры|Описание|
|---------|--------|
|counter_id|Идентификатор счетчика|
|url|URL сайта, на котором установлен счетчик|


