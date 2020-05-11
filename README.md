# YellowYard.NET

Список разработок на платформе .NET для платформы 1С:Предприятие.

## Инструменты разработки

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [OneScript](https://github.com/EvilBeaver/OneScript) | Исполняющая среда скриптов на языке 1С | - | [Андрей Овсянкин](https://infostart.ru/profile/267027/) |
| [OneScript.Web](https://github.com/EvilBeaver/OneScript.Web) | MVC-движок сайтов на 1Script | - | [Андрей Овсянкин](https://infostart.ru/profile/267027/) |
| [Elisy .Net Bridge](http://www.1csoftware.com/dotnet) | внешний компонент для 1C:Предприятие. Библиотека Elisy.NetBridge.dll обеспечивает бесшовную и гармоничную интеграцию с .Net Framework посредством взаимодействия с Common Language Runtime (CLR) | - | [Сергей Карташев](https://infostart.ru/profile/40833/) |

## Работа с журналом регистрации

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [YY.EventLogReaderAssistant](https://github.com/YPermitin/YY.EventLogReaderAssistant) | Библиотека для чтения файлов журнала регистрации платформы 1С:Предприятие 8.x | [![NuGet version](https://badge.fury.io/nu/YY.EventLogReaderAssistant.svg)](https://badge.fury.io/nu/YY.EventLogReaderAssistant) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogExportAssistant.Core](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.Core) | Базовый пакет для экспорта данных журнала регистрации | ![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.Core.svg) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogExportAssistant.SQLServer](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.SQLServer) | Пакет для экспорта журнала регистрации в базу SQL Server | [![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.SQLServer.svg)](https://badge.fury.io/nu/YY.EventLogExportAssistant.SQLServer) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [YY.EventLogExportAssistant.PostgreSQL](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.PostgreSQL) | Пакет для экспорта журнала регистрации в базу PostgreSQL | ![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.PostgreSQL.svg) | [Пермитин Юрий](https://infostart.ru/profile/225415/) |
| [EventLogLoader](https://github.com/alekseybochkov/EventLogLoader) | Периодическая загрузка событий из журналов регистрации ИБ 1С:Предприятие 8 в базу MS SQL Server/MySQL или индекс ElasticSearch | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |

## Работа с технологическим журналом

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [OneSTools.LogCfg](https://github.com/akpaevj/OneSTools.LogCfg) | Библиотека для программного создания файла конфигурации технологического журнала | - | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [OneSTechLog](https://github.com/akpaevj/OneSTechLog) | Библиотека позволяет выполнять парсинг технологического журнала и получать каждое событие в нормализованном виде | [![Nuget](https://img.shields.io/nuget/v/OneSTechLog)](https://www.nuget.org/packages/OneSTechLog) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [tj_loader](https://github.com/alekseybochkov/tj_loader) | Приложение позволяет выполнить разбор текстовых файлов технологического журнала с расширением *.log на события и записать эти события в таблицу базы MS SQL. | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |

## Администрирование

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [ServiceInstaller1C](https://github.com/alekseybochkov/ServiceInstaller1C) | Простое добавление новых служб сервера 1С или изменение параметров у существующих | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [WebRAS](https://github.com/alekseybochkov/WebRAS) | Альтернативная Консоль администрирования сервера 1С 8.3 | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |

## Безопасность

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [PasswordChanger1C](https://github.com/alekseybochkov/PasswordChanger1C) | Сброс паролей пользователей для файловой, клиент-серверной базы 1С и хранилища конфигураций | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
| [V8PasswordEjector](https://github.com/YPermitin/V8PasswordEjector) | Сброс учетных записей для 1С:Предприятия 8.x | - | [Пермитин Юрий](https://infostart.ru/profile/225415/) |

## Системное

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [OneSTools.BracketsFile](https://github.com/akpaevj/OneSTools.BracketsFile) | Библиотека для парсинга внутрисистемного формата файлов 1С | [![Nuget](https://img.shields.io/nuget/v/OneSTools.BracketsFile)](https://www.nuget.org/packages/OneSTools.BracketsFile) | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [OneSTools.Database](https://github.com/akpaevj/OneSTools.Database) | Библиотека, предназначенная для чтения структуры конфигурации 1С из существующей базы данных | - | [Евгений Акпаев](https://infostart.ru/profile/457562/) |
| [MdInternals](https://github.com/elisy/MdInternals) | Анализатор и декомпилятор конфигураций платформы 1С:Предприятие | - | [Сергей Карташев](https://infostart.ru/profile/40833/) |

## Другое

| Разработка | Описание | Nuget | Автор |
| ---------- | -------- | ----- | ----- |
| [outlook-addin-for-1c-enterprise](https://github.com/alekseybochkov/outlook-addin-for-1c-enterprise) | Согласование документов 1С:Документооборот и 1С:Консолидация из Outlook 2010-2013 без запуска 1С | - | [Алексей Бочков](https://infostart.ru/profile/15301/) |
