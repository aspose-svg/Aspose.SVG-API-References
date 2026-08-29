---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IXPathResult SnapshotItem methode. Retourneert het item op de indexde positie in de snapshotcollectie. Als index groter dan of gelijk aan het aantal knopen in de lijst is, retourneert deze methode null. In tegenstelling tot het iteratorresultaat wordt de snapshot niet ongeldig, maar kan deze mogelijk niet overeenkomen met het huidige document als het is gewijzigd."
type: docs
weight: 90
url: /nl/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Retourneert het `index`-de item in de snapshotcollectie. Als `index` groter dan of gelijk is aan het aantal knooppunten in de lijst, retourneert deze methode `null`. In tegenstelling tot het iteratorresultaat wordt de snapshot niet ongeldig, maar kan deze mogelijk niet overeenkomen met het huidige document als het is gewijzigd.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Index in de snapshotcollectie. |

### Retourwaarde

De knoop op de `index`de positie in de `NodeList`, of `null` als dat geen geldige index is.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: opgegooid als `resultType` geen `UnorderedNodeSnapshot`-type of `OrderedNodeSnapshot`-type is. |

### Zie ook

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
