Основана на общепринятом формате XMLTV. Описание доступно по адресу: http://wiki.xmltv.org/index.php.

`<tv generator-info-name="EPG Service generator xmltv" generator-info-url="http://www.epgservice.ru">`

`<channel id="id канала">`

`<display-name lang="ru">Название канала</display-name>`

`<icon src="ссылка на логотип канала"/>`

`</channel>`

`<programme start="дата начала" stop="дата окончания" channel="id канала" event-id="id эфирного события">`

`<title lang="ru" id="id тв-контента">Название тв-контента</title>`

`<sub-title lang="ru" id="id части тв-контента">Название части тв-контента</sub-title>`

`<season>Номер сезона</season>`

`<episode-number>Номер серии</episode-number>`

`<part-number>Номер части серии</part-number>`

`<desc size="smile" lang="ru">`

`Текст короткого варианта синопсиса (до 120 зн.)`

`</desc>`

`<desc size="normal" lang="ru">`

`Текст нормального варианта синопсиса (121 - 250 зн.)`

`</desc>`

`<desc size="large" lang="ru">`

`Текст большого варианта синопсиса (251 - 1024 зн.)</desc>`

`<category lang="ru" id="id категории">Название категории</category>`

`<ganre lang="ru" id="id жанра 1">Название жанра 1</ganre>`

`<ganre lang="ru" id="id жанра N">Название жанра N</ganre>`

`<credits> <!-- Лица -->`

`<person id="id лица 1" type="тип лица 1">`

`<name lang="ru">ФИО лица 1</name>`

`<biography>биография</biography>`

`<icon type="тип картинки" position="ориентация картинки" src="ссылка на фото лица 1"/>`

`<icon type="тип картинки" position="ориентация картинки" src="ссылка на фото лица 1"/>`

`</person>`

`<person id="id лица N" type="тип лица N">`

`<name lang="ru">ФИО лица N</name>`

`<biography>биография</biography>`

`<icon type="тип картинки" position="ориентация картинки" src="ссылка на фото лица N"/>`

`<icon type="тип картинки" position="ориентация картинки" src="ссылка на фото лица N"/>`

`</person>`

`</credits>`

`<date>дата эфира</date>`

`<country lang="ru" id="id страны 1">Название страны 1</country>`

`<country lang="ru" id="id страны N">Название страны N</country>`

`<production lang="ru" id="id студии-производителя">Название студии-производителя 1</production>`

`<production lang="ru" id="id студии-производителя">Название студии-производителя N</production>`

`<year>Год производства</year>`

`<topic lang="ru" id="id темы 1">Название темы 1</topic>`

`<topic lang="ru" id="id темы N">Название темы N</topic>`

`<kinopoisk>рейтинг kinopoisk</kinopoisk>`

`<id-kinopoisk>id kinopoisk</id-kinopoisk>`

`<imdb>рейтинг imdb</imdb>`

`<id-imdb>id imdb</id-imdb>`

`<rating system="RU">`

`<value>возрастной рейтинг</value>`

`</rating>`

`<icon type="тип картинки" position="ориентация картинки" src="ссылка на картинку тв-контента"/>`

`<icon type="тип картинки" position="ориентация картинки" src="ссылка на картинку тв-контента"/>`

`<sport lang="ru" id="id вида спорта">Название вида спорта</sport>`

`<championship id="id чемпионата">`

`<name lang="ru">Название чемпионата</name>`

`<icon src="ссылка на логотип чемпионата"/>`

`</championship>`

`<sub-championship id="id этапа чемпионата">`

`<name lang="ru">Назване этапа чемпионата</name>`

`</sub-championship>`

`<rivals>`

`<rival id="id соперника 1" couple="номер пары соперников">`

`<name lang="ru">Название соперника 1</name>`

`<icon src="ссылка на логотип соперника 1"/>`

`</rival>`

`<rival id="id соперника 2" couple="номер пары соперников">`

`<name lang="ru">Название соперника 2</name>`

`<icon src="ссылка на логотип соперника 2"/>`
`</rival>`

`</rivals>`

`<live>признак прямой трансляции</live>`

`<premiere>признак премьерного показа</premiere>`

`<budget currency="валюта"/>Бюджет</budget>`

`<fees currency="валюта"/>Сборы в мире</fees>`

`<fees-ros currency="валюта"/>Сборы в Росии</fees-ros>`

`<awards>Награды</awards>`

`</programme>`