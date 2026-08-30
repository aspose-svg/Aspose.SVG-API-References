---
title: "Node.TextContent"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node TextContent property. Representerar nodens textinnehåll och dess underordnade"
type: docs
weight: 160
url: /sv/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

Representerar textinnehållet i noden och dess undernoder.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

En sträng eller null. Dess värde beror på situationen:

Om noden är ett dokument eller en doctype, `TextContent` returnerar null. Obs: För att få all text och CDATA-data för hela dokumentet, använd

```csharp
document.DocumentElement.TextContent
```

.Om noden är en CDATA-sektion, en kommentar, en bearbetningsinstruktion eller en textnod, returnerar `TextContent`, eller sätter, texten inom noden, d.v.s. [`NodeValue`](../nodevalue/). För andra nodtyper returnerar `TextContent` sammansättningen av `TextContent` för varje barnnod, exklusive kommentarer och bearbetningsinstruktioner.

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
