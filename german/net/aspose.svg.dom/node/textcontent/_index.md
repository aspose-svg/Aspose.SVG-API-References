---
title: "Node.TextContent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Node TextContent Eigenschaft. Stellt den Textinhalt des Knotens und seiner Nachkommen dar."
type: docs
weight: 160
url: /de/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

Stellt den Textinhalt des Knotens und seiner Nachkommen dar.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

Eine Zeichenkette oder null. Ihr Wert hängt von der Situation ab:

Wenn der Knoten ein Dokument oder ein Doctype ist, gibt `TextContent` null zurück. Hinweis: Um den gesamten Text und CDATA-Daten des gesamten Dokuments zu erhalten, verwenden Sie

```csharp
document.DocumentElement.TextContent
```

Wenn der Knoten ein CDATA-Abschnitt, ein Kommentar, eine Verarbeitungsanweisung oder ein Textknoten ist, gibt `TextContent` den Text im Knoten zurück oder setzt ihn, d. h. das [`NodeValue`](../nodevalue/). Für andere Knotentypen gibt `TextContent` die Verkettung des `TextContent` jedes Kindknotens zurück, wobei Kommentare und Verarbeitungsanweisungen ausgeschlossen werden.

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### Siehe auch

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
