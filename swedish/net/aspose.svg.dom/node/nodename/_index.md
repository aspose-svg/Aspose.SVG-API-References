---
title: "Node.NodeName"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node NodeName‑egenskap. Returnerar namnet på den aktuella noden som en sträng"
type: docs
weight: 80
url: /sv/net/aspose.svg.dom/node/nodename/
---
## Node.NodeName property

Returnerar namnet på den aktuella noden som en sträng.

```csharp
public abstract string NodeName { get; }
```

### Property Value

En sträng, värden för de olika nodtyperna är:

[`Attr`](../../attr/) - The value of Attr.name, that is the qualified name of the attribute.[`CDATASection`](../../cdatasection/) - The string "#cdata-section".[`Comment`](../../comment/) - The string "#comment".[`Document`](../../document/) - The string "#document".[`DocumentFragment`](../../documentfragment/) - The string "#document-fragment".[`DocumentType`](../../documenttype/) - The value of [`Name`](../../documenttype/name/)[`Element`](../../element/) - The value of [`TagName`](../../element/tagname/), that is the uppercase name of the element tag if an HTML element, or the lowercase element tag if an XML element (like an SVG or MATHML element).[`ProcessingInstruction`](../../processinginstruction/) - The value of [`Target`](../../processinginstruction/target/)[`Text`](../../text/) - The string "#text".

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-nodename).

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
