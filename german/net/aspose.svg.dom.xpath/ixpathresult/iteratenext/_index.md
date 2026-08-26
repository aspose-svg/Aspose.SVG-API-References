---
title: "IXPathResult.IterateNext"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IXPathResult IterateNext‑Methode. Durchläuft und gibt den nächsten Knoten aus dem Knotensatz zurück oder null, wenn keine weiteren Knoten vorhanden sind"
type: docs
weight: 80
url: /de/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Iteriert und gibt den nächsten Knoten aus dem Knotensatz zurück oder `null`, wenn keine weiteren Knoten mehr vorhanden sind.

```csharp
public Node IterateNext()
```

### Rückgabewert

Gibt den nächsten Knoten zurück.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: ausgelöst, wenn `resultType` nicht vom Typ `UnorderedNodeIterator` oder `OrderedNodeIterator` ist. |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Das Dokument wurde verändert, seit das Ergebnis zurückgegeben wurde. |

### Siehe auch

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
