---
title: "NamedNodeMap Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Collections.NamedNodeMap class. Vertegenwoordigt collecties van attributen die op naam benaderd kunnen worden."
type: docs
weight: 2020
url: /nl/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

Vertegenwoordigt collecties van attributen die op naam benaderd kunnen worden.

```csharp
public class NamedNodeMap : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | Retourneert het index-de item in de map. Als de index groter dan of gelijk is aan het aantal knooppunten in deze map, wordt null geretourneerd. (2 indexers) |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | Het aantal knooppunten in deze map. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | Haalt een knooppunt op dat gespecificeerd is door naam. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | Haalt een knooppunt op dat gespecificeerd is door lokale naam en namespace-URI. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | Verwijdert een knooppunt gespecificeerd door naam. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | Verwijdert een knooppunt gespecificeerd door lokale naam en namespace-URI. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | Voegt een knooppunt toe met behulp van zijn nodeName‑attribuut. Als er al een knooppunt met die naam aanwezig is in deze map, wordt het vervangen door het nieuwe. Een knooppunt door zichzelf vervangen heeft geen effect. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | Voegt een knooppunt toe met behulp van zijn namespaceURI en localName. Als er al een knooppunt met die namespace‑URI en die lokale naam aanwezig is in deze map, wordt het vervangen door het nieuwe. Een knooppunt door zichzelf vervangen heeft geen effect. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
