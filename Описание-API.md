
## Индексный файл для машинного чтения.

Файл предназначен для получения ссылок на расписания заказанных каналов. Предоставляет сведения о заказанном списке каналов, дате последних изменений на канале определенной недели.
Запрос индексного файла производиться по ссылке:
`http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/index`

Файл содержит:

`* Список каналов заказчика,`

`* Даты обновления программы каналов <update>,`

`* Ссылку на географию (зона вещания канала)<geo-data>,`

`* Ссылки на полные расписания каналов на определенную неделю <href>:`

`* Неделя расписания <week>`

`* Ссылку на логотип канала <icon src>`

**Пример:**

`<geo-data>http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/geodata/000000066</geo-data>`

`<broadcast-city></code></pre>`

`<city id="0000204">Ростов-на-Дону</city>`

`<city id="0000238">Таганрог</city>`

`<city id="0000249">Тула</city>`

`</broadcast-city>`



**ВАЖНО! В файле может быть несколько блоков для одного канала. По одному блоку на каждую неделю расписания.**
Наглядная версия индексного файла со списком каналов и ссылкой на ТВ контента канала
<pre><code>http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/indexhtml</code></pre>

## Получение расписания канала без использования индексного файла
Расписание телеканала доступно через GET запрос:
<pre><code>http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/file/[ID_канала]</code></pre>

**Пример:**

<pre><code>http://xmldata.epgservice.ru/EPGService/hs/xmldata/OPERATOR/file/000000452</code></pre>

Программа на текущую неделю доступна по ссылке:
<pre><code>http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/file/[id канала]
</code></pre>
Программа на конкретную неделю: нужно указать параметр "week" - начало недели (понедельник):
<pre><code>http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/file/[id канала]?week=yyyy-mm-dd</code></pre>
(где dd - день, mm- месяц, yyyy – год).`

## География (зона вещания канала).


**Пример:**

`<geo-data>http://xmldata.epgservice.ru/EPGService/hs/xmldata/[ID_клиента]/geodata/000000066</geo-data>`

`<broadcast-city>`

`<city id="0000204">Ростов-на-Дону</city>`

`<city id="0000238">Таганрог</city>`

`<city id="0000249">Тула</city>`

`</broadcast-city>`

Запись свидетельствует о городах, в которых доступен канал.
В данном примере указано, что канал с id 000000066 доступен в городах: Ростов-на-Дону, Таганрог, Тула.