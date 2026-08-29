---
title: "Класс Location"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Window.Location. Объекты Location предоставляют представление адреса активного документа их контекста просмотра Documents и позволяют изменять текущую запись истории сеанса контекста просмотра, добавляя или заменяя записи в объекте истории."
type: docs
weight: 5950
url: /ru/net/aspose.svg.window/location/
---
## Location class

Объекты Location предоставляют представление адреса активного документа их контекста просмотра Document и позволяют изменять текущую запись истории сеанса контекста просмотра, добавляя или заменяя записи в объекте history.

```csharp
public sealed class Location : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | Возвращает фрагмент URL объекта Location (включает начальный "#", если он не пустой). Может быть установлен, чтобы перейти к тому же URL с изменённым фрагментом (игнорирует начальный "#"). |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | Возвращает хост и порт URL объекта Location (если они отличаются от порта по умолчанию для схемы). Может быть установлен, чтобы перейти к тому же URL с изменённым хостом и портом. |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | Возвращает хост URL объекта Location. Может быть установлен, чтобы перейти к тому же URL с изменённым хостом. |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | Возвращает URL объекта Location. Может быть установлен, чтобы перейти к указанному URL. |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | Возвращает origin URL объекта Location. |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | Возвращает путь URL объекта Location. Может быть установлен, чтобы перейти к тому же URL с изменённым путём. |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | Возвращает порт URL объекта Location. Может быть установлен, чтобы перейти к тому же URL с изменённым портом. |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | Возвращает схему URL объекта Location. Может быть установлен, чтобы перейти к тому же URL с изменённой схемой. |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | Возвращает запрос (query) URL объекта Location (включает начальный "?", если он не пустой). Может быть установлен, чтобы перейти к тому же URL с изменённым запросом (игнорирует начальный "?"). |

## Методы

| Имя | Описание |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | Переходит к указанной странице. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [Reload](../../aspose.svg.window/location/reload/)() | Перезагружает текущую страницу. |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | Удаляет текущую страницу из истории сеанса и переходит к указанной странице. |
| override [ToString](../../aspose.svg.window/location/tostring/)() | Возвращает URL объекта Location. |

### См. также

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
