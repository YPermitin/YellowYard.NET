# YellowYard.NET

Список разработок на платформе .NET для платформы 1С:Предприятие, а также некоторые связанные статьи и другие материалы.

## Инструменты разработки

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [OneScript](https://github.com/EvilBeaver/OneScript) | Исполняющая среда скриптов на языке 1С | - | [Андрей Овсянкин](https://infostart.ru/profile/267027/) |
| [OneScript.Web](https://github.com/EvilBeaver/OneScript.Web) | MVC-движок сайтов на 1Script | - | [Андрей Овсянкин](https://infostart.ru/profile/267027/) |
| [Elisy .Net Bridge](http://www.1csoftware.com/dotnet) | внешний компонент для 1C:Предприятие. Библиотека Elisy.NetBridge.dll обеспечивает бесшовную и гармоничную интеграцию с .Net Framework посредством взаимодействия с Common Language Runtime (CLR) | - | [Сергей Карташев](https://infostart.ru/profile/40833/) |
| [NetObjectToIDispatch](https://infostart.ru/public/238584/) | Использования сборок .Net в 1С через преобразование объектов и классов в COM-объекты, которые можно использовать в 1С | - | [Сергей Смирнов](https://infostart.ru/profile/82159/) |
| [1C# (OneCSharp)](https://github.com/zhichkin/one-c-sharp) | 1C# - это платформа для разработки серверных приложений, доступных через web | - | [Дмитрий Жичкин](https://infostart.ru/profile/525991/) |
| [YY.DotNetObjectWrapper](https://github.com/YPermitin/YY.DotNetObjectWrapper) | Оболочка объектов .NET для использования в других экосистемах приложений. Сейчас основной целью является использование для платформы 1С:Предприятие 8.x из кода встроенного языка. Это экспериментальный проект и в дальнейшем планируется глубокая модицификация библиотеки и некоторые эксперименты с ней. Основывается на базе библиотеке [NetObjetToIDispatch45 ](https://infostart.ru/public/238584/) | - | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [1SCodeAnalyze](https://github.com/znsoft/1SCodeAnalyze) | Анализатор кода 1С, автоматический код-ревью, статический анализ кода 1C | - | [znsoft](https://github.com/znsoft) |
| [1CAddin](https://github.com/SergeyMironchuk/1CAddin) | Шаблонный проект для создания внешней компонеты 1С на C# | - | [Sergey Mironchuk](https://github.com/SergeyMironchuk) |

## Работа с журналом регистрации

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [Экспорт журнала регистрации. Набор инструментов (приложения + исходный код)](https://infostart.ru/public/1240376/) | Набор инструментов для экспорта данных журнала регистрации во внешние хранилища для Windows и Linux. Готовые приложения и исходный код. | - | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogReaderAssistant](https://github.com/YPermitin/YY.EventLogReaderAssistant) | Библиотека для чтения файлов журнала регистрации платформы 1С:Предприятие 8.x | [![NuGet version](https://badge.fury.io/nu/YY.EventLogReaderAssistant.svg)](https://badge.fury.io/nu/YY.EventLogReaderAssistant) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogExportAssistant.Core](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.Core) | Базовый пакет для экспорта данных журнала регистрации | ![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.Core.svg) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogExportAssistant.SQLServer](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.SQLServer) | Пакет для экспорта журнала регистрации в базу SQL Server | [![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.SQLServer.svg)](https://badge.fury.io/nu/YY.EventLogExportAssistant.SQLServer) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogExportAssistant.PostgreSQL](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.PostgreSQL) | Пакет для экспорта журнала регистрации в базу PostgreSQL | ![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.PostgreSQL.svg) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [EventLogLoader](https://github.com/alekseybochkov/EventLogLoader) | Периодическая загрузка событий из журналов регистрации ИБ 1С:Предприятие 8 в базу MS SQL Server/MySQL или индекс ElasticSearch | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [OnecLogElasticSentry](https://github.com/PashaMak/OnecLogElasticSentry) | Журнал регистрации в эластике с использованием службы без использования 1С (.net + elastic) | - | [PashaMak](https://infostart.ru/profile/144011/) |
| [OneSTools.EventLog](https://github.com/akpaevj/OneSTools.EventLog) | Библиотеки и готовые инструменты для чтения и экспорта журнала регистрации 1С в ClickHouse и ElasticSearch | ![Nuget](https://img.shields.io/nuget/v/OneSTools.EventLog) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
 
## Работа с технологическим журналом

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [OneSTools.LogCfg](https://github.com/akpaevj/OneSTools.LogCfg) | Библиотека для программного создания файла конфигурации технологического журнала | [![Nuget](https://img.shields.io/nuget/v/OneSTools.LogCfg)](https://www.nuget.org/packages/OneSTools.LogCfg) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [OneSTools.TechLog](https://github.com/akpaevj/OneSTools.TechLog) | Библиотека позволяет выполнять парсинг технологического журнала и получать каждое событие в нормализованном виде | [![Nuget](https://img.shields.io/nuget/v/OneSTools.TechLog)](https://www.nuget.org/packages/OneSTechLog) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [tj_loader](https://github.com/alekseybochkov/tj_loader) | Приложение позволяет выполнить разбор текстовых файлов технологического журнала с расширением *.log на события и записать эти события в таблицу базы MS SQL. | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |

## Интеграция

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [simple-1c](https://github.com/ivan816/simple-1c) | Транслятор запросов и Linq-провайдер для 1С-Бухгалтерии | - | [ivan816](https://github.com/ivan816/simple-1c) |
| [WarehouseManager.CF.WinCE](https://github.com/znsoft/znsoftWarehouseManager.CF.WinCE) | Программа для работы со складской ИБД 1С через ВебСервис WinCE .CF | - | [znsoft](https://github.com/znsoft) |
| [RabbitMQ-Service-1C-Enterprise](https://github.com/pbazeliuk/RabbitMQ-Service-1C-Enterprise) | Создание Windows C# сервиса для оповещения «1С:Предприятия 8» об событиях RabbitMQ | - | [Petro Bazeliuk](https://github.com/pbazeliuk) |

## Администрирование

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [ServiceInstaller1C](https://github.com/alekseybochkov/ServiceInstaller1C) | Простое добавление новых служб сервера 1С или изменение параметров у существующих | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [WebRAS](https://github.com/alekseybochkov/WebRAS) | Альтернативная Консоль администрирования сервера 1С 8.3 | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [OneCleaner](https://github.com/vbondarevsky/OneCleaner) | Средство для удаления неиспользуемых версий 1С:Предприятие 8, кэша метаданных и информационных баз | - | [Vladimir Bondarevskiy](https://github.com/vbondarevsky) |
| [LicDataDecoder](https://github.com/GeraltSnow/LicDataDecoder) | Декодер файлов лицензий 1с. Извлечение LicData, сравнение параметров текущего компьютера с параметрами из лицензии. | - | [GeraltSnow](https://github.com/GeraltSnow) |
| [ZabbixStatistics](https://github.com/LLIKIPER/ZabbixStatistics) | Статистика выполнения кода из 1C в zabbix | - | [LLIKIPER](https://github.com/LLIKIPER) |
| [ClearCache1C](https://github.com/djserega/ClearCache1C) | Очистка кеша всех баз 1С текущего пользователя | - | [djserega](https://github.com/djserega) |
| [AdminPanel](https://github.com/akpaevj/AdminPanel) | Сайт с http-сервисом WebCommonInoBases для управления и раздачи списков баз 1С | - | [Евгений Акпаев](https://github.com/akpaevj) |

## Безопасность

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [PasswordChanger1C](https://github.com/alekseybochkov/PasswordChanger1C) | Сброс паролей пользователей для файловой, клиент-серверной базы 1С и хранилища конфигураций | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [V8PasswordEjector](https://github.com/YPermitin/V8PasswordEjector) | Сброс учетных записей для 1С:Предприятия 8.x | - | [Пермитин Юрий](https://infostart.ru/profile/225415/) |

## Системное

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [OneSTools.BracketsFile](https://github.com/akpaevj/OneSTools.BracketsFile) | Библиотека для парсинга внутрисистемного формата файлов 1С | [![Nuget](https://img.shields.io/nuget/v/OneSTools.BracketsFile)](https://www.nuget.org/packages/OneSTools.BracketsFile) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [OneSTools.Database](https://github.com/akpaevj/OneSTools.Database) | Библиотека, предназначенная для чтения структуры конфигурации 1С из существующей базы данных | [![Nuget](https://img.shields.io/nuget/v/OneSTools.Database)](https://www.nuget.org/packages/OneSTools.Database) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [V8Formats](https://github.com/YPermitin/V8Formats) | Распаковка в файловую структуру и запаковка в форматы файлов платформы 1С:Предприятие файлов конфигураций (.CF), внешних обработок (.ERF) и внешних отчетов (*.ERT) | [![NuGet version](https://badge.fury.io/nu/V8Formats.svg)](https://badge.fury.io/nu/V8Formats) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [MdInternals](https://github.com/elisy/MdInternals) | Анализатор и декомпилятор конфигураций платформы 1С:Предприятие | - | [Сергей Карташев](https://infostart.ru/profile/40833/) |

## Другое

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [outlook-addin-for-1c-enterprise](https://github.com/alekseybochkov/outlook-addin-for-1c-enterprise) | Согласование документов 1С:Документооборот и 1С:Консолидация из Outlook 2010-2013 без запуска 1С | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [1C-ERP-OLAP](https://github.com/PredictGroup/1C-ERP-OLAP) | OLAP ITL-Утилиты для 1С:ERP Управление предприятием | - | [PredictGroup Ltd.](https://github.com/PredictGroup) |
| [Dushelov.PDFViewer1C](https://github.com/DmitryDreytser/Dushelov.PDFViewer1C) | Просмотр PDF в 1С | - | [DmitryDreytser](https://github.com/DmitryDreytser) |
| [KillerOfUnwantedWindows1C](https://github.com/milkin-vl/KillerOfUnwantedWindows1C) | Программа "Убийца нежелательных окон 1С" (для платформы 1С версии 8) | - | [Vladimir Milkin](https://github.com/milkin-vl) |

## Интересные статьи

Различные статьи и материалы по использованию возможностей .NET при разработке на платформе 1С:Предприятие.

### Использование компоненты [NetObjectToIDispatch](https://infostart.ru/public/238584/):

<details>
    <summary>Список публикаций</summary>
 
* [Использование сборок .NET в 1С 7.x b 8.x. Создание внешних Компонент](https://infostart.ru/public/238584/)
* [Обработка для формирования классов для прямого доступа к файлам 1С через курсоры BDE. И многого другого](https://infostart.ru/public/345658/)
* [Методы для группировки данных по полю,полям в Таблице Значений на примере универсального метода списания по партиям, а также отбора строк в ТЗ по произвольному условию. Для 8.x и 7.7](https://infostart.ru/public/371762/)
* [ИзСтрокиСРазделителями в Восьмерке](https://infostart.ru/public/371887/)
* [Code First и Linq to EF на примере 1С версии 7.7 и 8.3 часть I](https://infostart.ru/public/393228/)
* [Code First и Linq to EF на примере 1С версии 8.3 часть II](https://infostart.ru/public/402038/)
* [Linq to EF. Практика использования. Часть III](https://infostart.ru/public/402433/)
* [Linq to ODATA](https://infostart.ru/public/403524/)
* [.NET(C#) для 1С. Динамическая компиляция класса обертки для использования .Net событий в 1С через ДобавитьОбработчик или ОбработкаВнешнегоСобытия](https://infostart.ru/public/417830/)
* [1C Messenger для отправки сообщений, файлов и обмена данными между пользователями 1С, вэб страницы, мобильными приложениями а ля Skype, WhatsApp](https://infostart.ru/public/434771/)
* [Использование классов .Net в 1С для новичков](https://infostart.ru/public/448668/)
* [Быстрое создание Внешних Компонент на C#. Примеры использования Глобального Контекста, IAsyncEvent, IExtWndsSupport, WinForms и WPF](https://infostart.ru/public/457898/)
* [.Net в 1С. Асинхронные HTTP запросы, отправка Post нескольких файлов multipart/form-data, сжатие трафика с использованием gzip, deflate, удобный парсинг сайтов и т.д.](https://infostart.ru/public/466052/)
* [.Net в 1С. На примере использования HTTPClient, AngleSharp. Удобный парсинг сайтов с помощью библиотеки AngleSharp, в том числе с авторизацией аля JQuery с использованием CSS селекторов. Динамическая компиляция](https://infostart.ru/public/466196/)
* [Использование ТСД на WM 6 как беспроводной сканер с получением данных из 1С](https://infostart.ru/public/525806/)
* [Кроссплатформенное использование классов .Net в 1С через Native ВК. Или замена COM на Linux](https://infostart.ru/public/534901/)
* [Кроссплатформенное использование классов .Net в 1С через Native ВК. Или замена COM на Linux II](https://infostart.ru/public/541518/)
* [Асинхронное программирование в 1С через использование классов .Net из Native ВК](https://infostart.ru/public/541698/)
* [1С, Linux, Excel, Word, OpenXML, ADO, Net Core](https://infostart.ru/public/544232/)
* [.Net Core, 1C, динамическая компиляция, Scripting API](https://infostart.ru/public/547389/)
* [Net Core. Динамическая компиляция класса обертки для получения событий .Net объекта в 1С](https://infostart.ru/public/548701/)
* [.Net Core, обмен с 1C по TCP/IP между различными устройствами](https://infostart.ru/public/551698/)

</details>

### Про Elisy .Net Bridge

<details>
    <summary>Список публикаций</summary>

* [1С.Net:Предприятие - подключите .Net Framework к 1C через Elisy .Net Bridge](https://infostart.ru/public/20035/)
* [1C.Net:Предприятие - Инструкция по подключению Elisy .Net Bridge 4 на 64-разрядном сервере 1С:Предприятие 8](https://infostart.ru/public/165910/)
* [1C.Net:Предприятие – использование богатых графических возможностей .Net Framework](https://infostart.ru/public/70417/)
* [Фотография на документы. Интерактивный редактор](https://infostart.ru/public/78946/)

</details>

### Другие статьи

<details>
    <summary>Список публикаций</summary>
 
* [1C.Net:Предприятие – пример коммерческого успеха .Net-решений в России](https://infostart.ru/public/70859/)
* [Работа с журналом регистрации. Выходим за границы платформы](https://infostart.ru/public/1234678/)
* [Сложнейшая загрузка журнала регистрации в ElasticSearch (или делаем настоящий ETL)](https://infostart.ru/public/1128327/)

</details>
