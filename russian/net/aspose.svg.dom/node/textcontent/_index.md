---
title: "Node.TextContent"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство Node TextContent. Представляет текстовое содержимое узла и его потомков"
type: docs
weight: 160
url: /ru/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

Представляет текстовое содержимое узла и его потомков.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

Строка или null. Ее значение зависит от ситуации:

Если узел является документом или типом документа, `TextContent` возвращает null. Примечание: чтобы получить весь текст и данные CDATA для всего документа, используйте

```csharp
document.DocumentElement.TextContent
```

.Если узел является секцией CDATA, комментарием, инструкцией обработки или текстовым узлом, `TextContent` возвращает или задает текст внутри узла, то есть [`NodeValue`](../nodevalue/). Для других типов узлов `TextContent` возвращает конкатенацию `TextContent` всех дочерних узлов, исключая комментарии и инструкции обработки.

## Замечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### См. также

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
