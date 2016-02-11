#Отчеты

Отчеты предоставляют статистическую информацию о сайте и обращениях посетителей.
Каждый отчет содержит показатели, объединенные в группы (например, по типу трафика). Отчет строится за определенный период времени. По умолчанию он соответствует месяцу. Данные отображаются в таблице и на диаграмме.

##Настройка отчета

Ниже описаны инструменты, с помощью которых вы можете настроить вид отчета:
![Пример отчета](report_1.png)

##Список отчетов ![Цифра_1](dig_1.png)

Открывает список готовых отчетов. Данные отчеты рекомендуется использовать в качестве примера для создания собственных.
![Готовые отчеты](report_11.png)

##Выгрузка CSV ![Цифра_2](dig_2.png)

Позволяет выгружать отчет в формате CSV.
В выгрузке будут предоставлены данные:
- по указанным измерениям, метрикам 
- за выбранный период 
- с учетом активных фильтров.

##Метрики на диаграмме ![Цифра_3](dig_3.png)

Позволяет выбрать метрики, которые будут отображаться на диаграмме. Выбрать можно только добавленные в отчет метрики.  
![Метрики на диаграмме](report_41.png)
Круговая диаграмма отображает данные для 1 метрики. Линейная диаграмма позволяет отображать данные сразу для нескольких метрик.

##Период отчета ![Цифра_4](dig_4.png)
Вы можете выбрать календарный период времени, за который будет построен отчет. По умолчанию отображаются данные за месяц. Доступны стандартные диапазоны дат, также можно выбрать собственный диапазон.

![Период отчета](report_51.png)

##Виды диаграмм ![Цифра_5](dig_5.png)

Позволяет выбрать диагарамму, подходящую для конкретной задачи. В данный момент доступны следующие виды диаграмм:

**Линейная**<br/>
Показывает изменения абсолютных значений измеряемых величин во времени.

![Линейная диаграмма](report_62.png)

**Круговая**<br/>
Показывает распределение величин по группам.

![Круговая диаграмма](report_61.png)

##Формат отчета ![Цифра_6](dig_6.png)

Позволяет выбрать формат отображения данных. В данный момент доступны следующие форматы:

**Древовидный список**<br/>

Данные группируются **последовательно** по каждому выбранному измерению, формируя древовидную структуру.

![Древовидный список](report_601.png)

**Линейный список**<br/>
Данные группируются **одновременно** по всем выбранным измерениям, формируя линейную структуру.

![Древовидный список](report_602.png)

##Измерения ![Цифра_7](dig_7.png)

Позволяет выбрать измерения, по которым будут группироваться метрики. Для выбранных измерений можно задать порядок группировки.

![Выбор измерений](report_71.png)

**Порядок группировки данных**

Для одинакового набора измерений отображение данных будет отличаться в зависимости от последовательности группировки метрик. Ниже приведен пример отчета, сгруппированого по измерениям **Тип трафика**, **Источник**

![Пример группировки](report_72.png)

**Отображение на диаграмме**

Трекер позволяет отображать любой срез данных на диаграмме. Для отображения среза необоходимо кликнуть по полю слева от него:

![Отображение измерений на диаграмме](report_73.png)

В зависимости от выбранных сегментов поле может выглядеть следующим образом:
![Пустое поле](report_76.png) - сегмент не отображается на графике
![Активное поле](report_75.png) - сегмент отображается на графике
![Активно дочернее поле](report_74.png) - вложенный сегмент отображается на графике

##Метрики ![Цифра_8](dig_8.png)

Позволяет выбрать метрики, которые будут отображаться в отчете. Для выбранных метрик можно задать порядок отображения в отчете.

![Метрики](report_81.png)

**Сортировка данных**

Вы можете сортировать данные по определенной метрике. Для этого необходимо кликнуть в отчете на её название.

Сортировка будет осуществляться для каждой группировки в соответствии с их порядком.

![Сортировка метрик](report_82.png)

##Фильтры ![Цифра_9](dig_9.png)

Фильтры позволяют работать с данными, удовлетворяющими определенным условиям.
Условия могут применяться на метрики и измерения, выбранные в отчете (подробнее ниже).

![Настройка фильтра](report_21.png)

Используемые фильтры отображаются в отдельной панели, из которой их можно оперативно убрать.

![Примененные фильтры](report_22.png)