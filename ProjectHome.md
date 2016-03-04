![http://enterpriseintegrator.googlepages.com/Logo.gif](http://enterpriseintegrator.googlepages.com/Logo.gif)

<a href='http://www.youtube.com/watch?feature=player_embedded&v=2Hy7i9YJKT8' target='_blank'><img src='http://img.youtube.com/vi/2Hy7i9YJKT8/0.jpg' width='425' height=344 /></a>
# Требования #
1С:Предприятие 8.1.11 **и старше** в серверном варианте работы  (_возможно использовать и файловом режиме с некоторыми ограничениями_).
Поддерживаемые СУБД:
  * MSSQL2000,MSSQL2005,MSSQL2008,MSSQL2012;
  * PGSQL;
  * DB2 .

# Используемые ресурсы #
| **Имя** | **Ресурс** | **Цель** |
|:--------|:-----------|:---------|
|ADODB.Connection| Создание подключения к источнику данных по умолчанию эквивалентен текущему сетевому соединению с сервером. Выполнение параметризованных запросов| |
|ADODB.Recordset | Изменение данных в БД| |
|V81.Connector V82.Connector|  Подключение к серверу предприятия| |
|Excel.Application|  Выгрузка рузультатов в MS Excel| |
|WScript.Shell|  Для изменений значений реестра, снижения безопасности Excel (создание группировок). Регистрация библиотек (regsvr32) в случае необходимости| |
|OLAP.ocx | Построение OLAP кубов| |
|[GameWithFire](http://main.1c-ei.ru/Articles/gamewithfire/)|[GameWithFire.dll](http://main.1c-ei.ru/Articles/gamewithfire/), zlib1.dll автор Дмитрий Ощепков aka DmitrO| Внешняя компонента. Работа со служебными данными 1Cv8. Увеличивает скорость работы обработки при выгрузке результатов запроса SQL в таблицу.|
|[TechLog.dll](http://code.google.com/p/enterprise-integrator/) [TechLog\_na.dll](http://code.google.com/p/enterprise-integrator/)| Enterprise Integrator | Чтение технологического журнала |
|[GoldParser.dll](http://www.devincook.com/goldparser/)| Devincook  | Разбиение сложного запроса на составные части |
|[MSScriptControl.ScriptControl](http://msdn.microsoft.com/en-us/library/aa227633(v=vs.60).aspx)| MS         | Реализация паузы за счет выполнения JavaScript |
|[VBScript.RegExp](http://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%B3%D1%83%D0%BB%D1%8F%D1%80%D0%BD%D1%8B%D0%B5_%D0%B2%D1%8B%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F)| MS         | Выполнение регулярных выражений |
|[pcrelib.dll](http://en.wikipedia.org/wiki/PCRE)|            | Выполнение регулярных выражений |
|USBKeyLib\_EKWWT.win64.dll USBKeyLib\_EKWWT.win32.dll hasp\_windows\_x64\_99792.dll | Alladin    | Библиотеки защиты |
|qp.js, qp.css  | Justin Minnow| Представление плана запросов в HTML |



**Все алгоритмы и методики (не используемые в ресурсах) являются  интелектульной собственностью разработчиков. Авторы запрещают использование алгоритмов и методик опубликованных в данной обработке, без указания на данную разработку и авторов.**

# Авторы #

---

  * **Герман Кудяков**   Санкт-Петербург
  * **Дмитрий Аверин**   Москва
## Разработчики ##
  * **Дмитрий Ощепков**   Киров
  * **Лупашку Ион**   Болгария




