---
title: "Resource.Save"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Resource Save. Сохраняет ресурс в предоставленный поток."
type: docs
weight: 70
url: /ru/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Сохраняет ресурс в предоставленный поток.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который будет сохранён ресурс. |
| context | ResourceHandlingContext | Контекст обработки ресурса. |

### Возвращаемое значение

Этот ресурс, чтобы вы могли цепочкой вызывать методы.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Вызывается, если [`OutputUrl`](../outputurl/) равен `null`. [`OutputUrl`](../outputurl/) должен быть указан перед сохранением ресурса, иначе невозможно указать правильную ссылку в ресурсах, ссылающихся на этот. |

### См. также

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
