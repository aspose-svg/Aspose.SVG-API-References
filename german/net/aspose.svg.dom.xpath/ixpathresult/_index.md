---
title: "IXPathResult Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.XPath.IXPathResult Schnittstelle. Die XPathResult Schnittstelle stellt das Ergebnis der Auswertung eines XPath 1.0‑Ausdrucks im Kontext eines bestimmten Knotens dar. Da die Auswertung eines XPath‑Ausdrucks zu verschiedenen Ergebnistypen führen kann, ermöglicht dieses Objekt das Erkennen und Manipulieren des Typs und des Werts des Ergebnisses."
type: docs
weight: 3350
url: /de/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

Das `XPathResult`-Interface stellt das Ergebnis der Auswertung eines XPath‑1.0‑Ausdrucks im Kontext eines bestimmten Knotens dar. Da die Auswertung eines XPath‑Ausdrucks zu verschiedenen Ergebnis­typen führen kann, ermöglicht dieses Objekt das Erkennen und Manipulieren des Typs und des Werts des Ergebnisses.

```csharp
public interface IXPathResult
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | Der Wert dieses booleschen Ergebnisses. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Zeigt an, dass der Iterator ungültig geworden ist. True, wenn `resultType` vom Typ `UnorderedNodeIterator` oder `OrderedNodeIterator` ist und das Dokument seit der Rückgabe dieses Ergebnisses geändert wurde. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | Der Wert dieses Zahlenergebnisses. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Ein Code, der den Typ dieses Ergebnisses darstellt, wie definiert durch die http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) Enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Der Wert dieses einzelnen Knotenergebnisses, das `null` sein kann. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Die Anzahl der Knoten im Ergebnis‑Snapshot. Gültige Werte für snapshotItem‑Indizes sind `0` bis `snapshotLength-1` inklusive. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | Der Wert dieses Zeichenketten­ergebnisses. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Iteriert und gibt den nächsten Knoten aus dem Knotensatz zurück oder `null`, wenn keine weiteren Knoten mehr vorhanden sind. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | Gibt das `index`‑te Element in der Snapshot‑Sammlung zurück. Wenn `index` größer oder gleich der Anzahl der Knoten in der Liste ist, liefert diese Methode `null`. Im Gegensatz zum Iterator‑Ergebnis wird der Snapshot nicht ungültig, kann jedoch bei einer Veränderung des Dokuments nicht mehr dem aktuellen Dokument entsprechen. |

### Siehe auch

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
