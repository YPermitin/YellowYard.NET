# YellowYard.NET

Список разработок на платформе .NET для платформы 1С:Предприятие.

## Инструменты разработки

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [OneScript](https://github.com/EvilBeaver/OneScript) | Исполняющая среда скриптов на языке 1С | - |
| [OneScript.Web](https://github.com/EvilBeaver/OneScript.Web) | MVC-движок сайтов на 1Script | - |
| [Elisy .Net Bridge](http://www.1csoftware.com/dotnet) | внешний компонент для 1C:Предприятие. Библиотека Elisy.NetBridge.dll обеспечивает бесшовную и гармоничную интеграцию с .Net Framework посредством взаимодействия с Common Language Runtime (CLR) | - |

## Работа с журналом регистрации

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [YY.EventLogReaderAssistant](https://github.com/YPermitin/YY.EventLogReaderAssistant) | Библиотека для чтения файлов журнала регистрации платформы 1С:Предприятие 8.x | [![NuGet version](https://badge.fury.io/nu/YY.EventLogReaderAssistant.svg)](https://badge.fury.io/nu/YY.EventLogReaderAssistant) | 
| [YY.EventLogExportAssistant.Core](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.Core) | Базовый пакет для экспорта данных журнала регистрации | ![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.Core.svg) |
| [YY.EventLogExportAssistant.SQLServer](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.SQLServer) | Пакет для экспорта журнала регистрации в базу SQL Server | [![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.SQLServer.svg)](https://badge.fury.io/nu/YY.EventLogExportAssistant.SQLServer) |
| [YY.EventLogExportAssistant.PostgreSQL](https://github.com/YPermitin/YY.EventLogExportAssistant/tree/master/Libs/YY.EventLogExportAssistant.PostgreSQL) | Пакет для экспорта журнала регистрации в базу PostgreSQL | ![NuGet version](https://badge.fury.io/nu/YY.EventLogExportAssistant.PostgreSQL.svg) |
| [EventLogLoader](https://github.com/alekseybochkov/EventLogLoader) | Периодическая загрузка событий из журналов регистрации ИБ 1С:Предприятие 8 в базу MS SQL Server/MySQL или индекс ElasticSearch | - |

## Работа с технологическим журналом

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [OneSTools.LogCfg](https://github.com/akpaevj/OneSTools.LogCfg) | Библиотека для программного создания файла конфигурации технологического журнала | - |
| [OneSTechLog](https://github.com/akpaevj/OneSTechLog) | Библиотека позволяет выполнять парсинг технологического журнала и получать каждое событие в нормализованном виде | [![Nuget](https://img.shields.io/nuget/v/OneSTechLog)](https://www.nuget.org/packages/OneSTechLog) |
| [tj_loader](https://github.com/alekseybochkov/tj_loader) | Приложение позволяет выполнить разбор текстовых файлов технологического журнала с расширением *.log на события и записать эти события в таблицу базы MS SQL. | - |

## Администрирование

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [ServiceInstaller1C](https://github.com/alekseybochkov/ServiceInstaller1C) | Простое добавление новых служб сервера 1С или изменение параметров у существующих | - |
| [WebRAS](https://github.com/alekseybochkov/WebRAS) | Альтернативная Консоль администрирования сервера 1С 8.3 | - |

## Безопасность

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [PasswordChanger1C](https://github.com/alekseybochkov/PasswordChanger1C) | Сброс паролей пользователей для файловой, клиент-серверной базы 1С и хранилища конфигураций | - |
| [V8PasswordEjector](https://github.com/YPermitin/V8PasswordEjector) | Сброс учетных записей для 1С:Предприятия 8.x | - |

## Системное

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [OneSTools.BracketsFile](https://github.com/akpaevj/OneSTools.BracketsFile) | Библиотека для парсинга внутрисистемного формата файлов 1С | [![Nuget](https://img.shields.io/nuget/v/OneSTools.BracketsFile)](https://www.nuget.org/packages/OneSTools.BracketsFile) |
| [OneSTools.Database](https://github.com/akpaevj/OneSTools.Database) | Библиотека, предназначенная для чтения структуры конфигурации 1С из существующей базы данных | - |
| [MdInternals](https://github.com/elisy/MdInternals) | Анализатор и декомпилятор конфигураций платформы 1С:Предприятие | - |

## Другое

| Разработка | Описание | Nuget |
| ---------- | -------- | ----- |
| [outlook-addin-for-1c-enterprise](https://github.com/alekseybochkov/outlook-addin-for-1c-enterprise) | Согласование документов 1С:Документооборот и 1С:Консолидация из Outlook 2010-2013 без запуска 1С | - |
