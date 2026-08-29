---
title: "Document.CreateElement"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document CreateElement. Создаёт HTML‑элемент, указанный в localName, или HTMLUnknownElement, если localName не распознан."
type: docs
weight: 850
url: /ru/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

Создаёт HTML‑элемент, указанный в localName, или HTMLUnknownElement, если localName не распознан.

```csharp
public Element CreateElement(string localName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Строка, указывающая тип создаваемого элемента. nodeName созданного элемента инициализируется значением localName. Не используйте квалифицированные имена (например, "html:a") с этим методом. При вызове в HTML‑документе createElement() преобразует localName в нижний регистр перед созданием элемента. |

### Возвращаемое значение

Новый [`Element`](../../element/).

### См. также

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
