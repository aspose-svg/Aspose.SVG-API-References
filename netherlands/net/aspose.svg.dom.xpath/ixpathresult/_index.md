---
title: "IXPathResult interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.XPath.IXPathResult interface. De XPathResult interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0-expressie binnen de context van een bepaald knooppunt. Aangezien de evaluatie van een XPath-expressie kan resulteren in verschillende resultaatstypen, maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren."
type: docs
weight: 3350
url: /nl/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

De `XPathResult` interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0-expressie binnen de context van een specifieke knoop. Aangezien de evaluatie van een XPath-expressie kan resulteren in verschillende resultaatssoorten, maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren.

```csharp
public interface IXPathResult
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | De waarde van dit booleaanse resultaat. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Geeft aan dat de iterator ongeldig is geworden. Waar (`true`) als `resultType` van het type `UnorderedNodeIterator` of `OrderedNodeIterator` is en het document is gewijzigd sinds dit resultaat werd geretourneerd. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | De waarde van dit numerieke resultaat. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Een code die het type van dit resultaat weergeeft, zoals gedefinieerd door de http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | De waarde van dit enkele knooppuntresultaat, die `null` kan zijn. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Het aantal knooppunten in de resultaatsnapshot. Geldige waarden voor snapshotItem-indexen zijn `0` tot en met `snapshotLength-1`. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | De waarde van dit tekenreeksresultaat. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Itereert en retourneert het volgende knooppunt uit de knooppuntset of `null` als er geen knooppunten meer zijn. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | Retourneert het `index`-de item in de snapshotcollectie. Als `index` groter dan of gelijk is aan het aantal knooppunten in de lijst, retourneert deze methode `null`. In tegenstelling tot het iteratorresultaat wordt de snapshot niet ongeldig, maar kan deze mogelijk niet overeenkomen met het huidige document als het is gewijzigd. |

### Zie ook

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
