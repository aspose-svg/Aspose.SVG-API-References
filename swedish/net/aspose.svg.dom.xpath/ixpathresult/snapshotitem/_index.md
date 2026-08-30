---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.SVG för .NET API-referens"
description: "IXPathResult SnapshotItem-metod. Returnerar det indexte elementet i snapshot-samlingen. Om index är större än eller lika med antalet noder i listan returnerar denna metod null. Till skillnad från iteratorresultatet blir snapshotet inte ogiltigt men kan eventuellt inte motsvara det aktuella dokumentet om det har förändrats"
type: docs
weight: 90
url: /sv/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Returnerar det `index`:e objektet i snapshot‑samlingen. Om `index` är större än eller lika med antalet noder i listan returnerar denna metod `null`. Till skillnad från iteratorresultatet blir snapshotet inte ogiltigt, men kan eventuellt inte motsvara det aktuella dokumentet om det har förändrats.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index i snapshot-samlingen. |

### Returvärde

Noden på `index`te position i `NodeList`, eller `null` om det inte är ett giltigt index.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: kastas om `resultType` inte är av typen `UnorderedNodeSnapshot` eller `OrderedNodeSnapshot`. |

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
