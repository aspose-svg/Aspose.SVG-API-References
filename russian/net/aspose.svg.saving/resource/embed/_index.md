---
title: "Resource.Embed"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Resource Embed. Встраивает этот ресурс в его родителя, кодируя его в Base64. Результат кодирования будет записан в OutputUrl."
type: docs
weight: 60
url: /ru/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Встраивает этот ресурс в его родителя, кодируя его в Base64. Результат кодирования будет записан в [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | ResourceHandlingContext | Контекст обработки ресурса. |

### Возвращаемое значение

Этот ресурс, чтобы вы могли цепочкой вызывать методы.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Вызывается, если нет [`ParentResource`](../../resourcehandlingcontext/parentresource/), потому что нет места для встраивания результата. |

### См. также

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
