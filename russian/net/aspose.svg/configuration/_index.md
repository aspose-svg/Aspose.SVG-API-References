---
title: "Класс Configuration"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Configuration class. Представляет объект контекста конфигурации, который используется для настройки параметров среды приложения"
type: docs
weight: 2050
url: /ru/net/aspose.svg/configuration/
---
## Configuration class

Представляет объект контекста конфигурации, который используется для настройки параметров среды приложения.

```csharp
public class Configuration : IDisposable, IServiceProvider
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Configuration](configuration/)() | Инициализирует новый экземпляр класса `Configuration`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Security](../../aspose.svg/configuration/security/) { get; set; } | Это свойство позволяет задать ряд ограничений на содержимое, загружаемое во фрейм, например, блокировать формы и скрипты. См. статью о [sandboxing](https://docs.aspose.com/html/net/environment-configuration/#sandboxing). |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.svg/configuration/create/#create)() | Создайте и настройте экземпляр объекта Configuration. |
| static [Create](../../aspose.svg/configuration/create/#create_1)(*Action&lt;IConfigurationBuilder&gt;*) | Создайте и настройте экземпляр объекта Configuration. |
| [Dispose](../../aspose.svg/configuration/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [GetService](../../aspose.svg/configuration/getservice/#getservice)(*Type*) | Получает запрошенный сервис. |
| [GetService<T>](../../aspose.svg/configuration/getservice/#getservice_1)() | Получает запрошенный сервис. |
| static [SetExtension](../../aspose.svg/configuration/setextension/)(*[IConfigurationExtension](../iconfigurationextension/)*) | Устанавливает расширение для конфигурации. |

### См. также

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
