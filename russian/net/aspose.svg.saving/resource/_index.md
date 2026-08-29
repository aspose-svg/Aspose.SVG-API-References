---
title: "Класс Resource"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Saving.Resource. Этот класс описывает ресурс и предоставляет методы для его обработки"
type: docs
weight: 5710
url: /ru/net/aspose.svg.saving/resource/
---
## Resource class

Этот класс описывает ресурс и предоставляет методы для его обработки.

```csharp
public class Resource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Возвращает !:Html.MimeType этого ресурса. Может быть `null`, если ресурс не найден. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Возвращает строку, содержащую исходную ссылку на этот ресурс. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Возвращает URL, указывающий, где находился этот ресурс. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Получает или задает URL, указывающий, где ресурс будет находиться после обработки. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Возвращает текущий статус ресурса. |

## Методы

| Имя | Описание |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Встраивает этот ресурс в его родительский элемент, кодируя его в Base64. Результат кодирования будет записан в [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Сохраняет ресурс в предоставленный поток. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Указывает новый URL, показывающий, где ресурс будет находиться после обработки. |

### См. также

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
