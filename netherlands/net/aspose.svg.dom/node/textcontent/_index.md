---
title: "Node.TextContent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Node TextContent eigenschap. Vertegenwoordigt de tekstinhoud van het knooppunt en zijn afstammelingen"
type: docs
weight: 160
url: /nl/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

Stelt de tekstinhoud van het knooppunt en zijn afstammelingen voor.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

Een string, of null. De waarde hangt af van de situatie:

Als het knooppunt een document of een doctype is, retourneert `TextContent` null. Opmerking: om alle tekst en CDATA-gegevens voor het hele document te verkrijgen, gebruik

```csharp
document.DocumentElement.TextContent
```

Als het knooppunt een CDATA-sectie, een commentaar, een verwerkingsinstructie of een tekstknooppunt is, retourneert `TextContent` of stelt de tekst binnen het knooppunt in, d.w.z. de [`NodeValue`](../nodevalue/). Voor andere knooppunttypes retourneert `TextContent` de samenvoeging van de `TextContent` van elk kindknooppunt, exclusief commentaren en verwerkingsinstructies.

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### Zie ook

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
