---
title: "Node.NodeName"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство Node NodeName. Возвращает имя текущего узла в виде строки."
type: docs
weight: 80
url: /ru/net/aspose.svg.dom/node/nodename/
---
## Node.NodeName property

Возвращает имя текущего узла в виде строки.

```csharp
public abstract string NodeName { get; }
```

### Property Value

Строка, значения для различных типов узлов:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The string "#cdata-section".[`Comment`](../../comment/) - The string "#comment".[`Document`](../../document/) - The string "#document".[`DocumentFragment`](../../documentfragment/) - The string "#document-fragment".[`DocumentType`](../../documenttype/) - The value of [`Name`](../../documenttype/name/)[`Element`](../../element/) - The value of [`TagName`](../../element/tagname/), that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like an SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of [`Target`](../../processinginstruction/target/)[`Text`](../../text/) - The string "#text".

## Замечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-nodename).

### См. также

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
