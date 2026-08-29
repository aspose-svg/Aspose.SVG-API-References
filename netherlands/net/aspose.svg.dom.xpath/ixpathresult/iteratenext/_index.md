---
title: "IXPathResult.IterateNext"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IXPathResult IterateNext methode. Itereert en retourneert de volgende knoop uit de knoopset of null als er geen knopen meer zijn."
type: docs
weight: 80
url: /nl/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Itereert en retourneert het volgende knooppunt uit de knooppuntset of `null` als er geen knooppunten meer zijn.

```csharp
public Node IterateNext()
```

### Retourwaarde

Retourneert de volgende knoop.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: opgegooid als `resultType` geen `UnorderedNodeIterator`-type of `OrderedNodeIterator`-type is. |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Het document is gewijzigd sinds het resultaat werd geretourneerd. |

### Zie ook

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
