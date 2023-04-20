---
title: Interface IXPathResult
second_title: Aspose.SVG voor .NET API-referentie
description: Aspose.Svg.Dom.XPath.IXPathResult koppel. DeXPathResult interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0expressie binnen de context van een bepaald knooppunt. Aangezien evaluatie van een XPathexpressie kan resulteren in verschillende resultaattypes maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren.
type: docs
weight: 1350
url: /nl/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

De`XPathResult` interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0-expressie binnen de context van een bepaald knooppunt. Aangezien evaluatie van een XPath-expressie kan resulteren in verschillende resultaattypes, maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren.

```csharp
public interface IXPathResult
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | De waarde van dit booleaanse resultaat. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Geeft aan dat de iterator ongeldig is geworden. Waar als`resultaatType` is`OngeordendeNodeIterator` typ of`OrderedNodeIterator` type en het document is gewijzigd sinds dit resultaat werd geretourneerd. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | De waarde van dit getalresultaat. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Een code die het type resultaat vertegenwoordigt, zoals gedefinieerd door de http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) opsomming. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | De waarde van dit enkele knooppuntresultaat, dat kan zijn`nul` . |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Het aantal knooppunten in de momentopname van het resultaat. Geldige waarden voor snapshotItem indices zijn`0` naar`snapshotLength-1` inclusief. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | De waarde van dit tekenreeksresultaat. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Itereert en retourneert het volgende knooppunt uit de knooppuntenset of`nul` als er geen nodes meer zijn. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(int) | Retourneert de`inhoudsopgave` e item in de snapshot-verzameling. Als`inhoudsopgave`groter is dan of gelijk is aan het aantal knooppunten in de lijst, retourneert deze methode`nul` . In tegenstelling tot het iteratorresultaat, wordt de momentopname niet ongeldig, maar komt deze mogelijk niet overeen met het huidige -document als het is gemuteerd. |

### Zie ook

* naamruimte [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* montage [Aspose.SVG](../../)


