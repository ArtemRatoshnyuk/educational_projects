# Статистика создания заказов мясокомбината

**Цель**

Выявление причин задержки сборки и доставки собранных заказов клиентам.

**Данные**

В наличии были следующие данные:
- файл с указанием поправки часового пояса торгового представителя к Уральскому времени
- табличное представление регистра сведений "Граница запрета заказов" с указанием дня недели и предельного времени подачи заказа торговым представителем
- группа файлов выгрузки (за каждый месяц) с указанием номера отгрузки и даты/времени каждой манипуляции с ней
- файл выгрузки с указанием данных о заказе за указанный период (сумма, вес, дата/время каждой манипуляции)
- файл выгрузки с указанием данных о заказе заморозки/полуфабрикаты за указанный период (сумма, вес, дата/время каждой манипуляции)формат ответа

**Задача**

Выявить причины, которые создают пиковую нагрузку работы склада

**Используемые библиотеки**

pandas, os, datetime, seaborn, matplotlib, nbconvert
