---
title: "Element.AttachShadow"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Element AttachShadow. Создаёт теневую корневую часть и присоединяет её к текущему элементу."
type: docs
weight: 220
url: /ru/net/aspose.svg.dom/element/attachshadow/
---
## Element.AttachShadow method

Создаёт shadow root и присоединяет его к текущему элементу.

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | ShadowRootMode | Режим, в котором будет создан теневой корень. |

### Возвращаемое значение

Создан [`ShadowRoot`](../../shadowroot/).

### Исключения

| исключение | условие |
| --- | --- |
| Ошибка | NotSupportedError: Элемент не поддерживает теневое дерево. |
| Ошибка | InvalidStateError: У элемента уже есть теневое дерево. |

### См. также

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
