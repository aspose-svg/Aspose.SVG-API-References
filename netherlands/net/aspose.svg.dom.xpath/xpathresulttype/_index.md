---
title: "XPathResultType enum"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.XPath.XPathResultType enum. Een unsigned short die aangeeft welk type resultaat dit is. Als een specifiek type is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type met behulp van XPath-typeconversies waar nodig en mogelijk."
type: docs
weight: 3360
url: /nl/net/aspose.svg.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Een unsigned short die aangeeft welk type resultaat dit is. Als een specifiek `type` is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type, met gebruik van XPath-typeconversies waar nodig en mogelijk.

```csharp
public enum XPathResultType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Any | `0` | Deze code vertegenwoordigt geen specifiek type. Een evaluatie van een XPath-expressie zal dit type nooit produceren. Als dit type wordt aangevraagd, retourneert de evaluatie welk type dan ook dat natuurlijk voortvloeit uit de evaluatie van de expressie. Als het natuurlijke resultaat een knooppuntset is wanneer het type `Any` werd aangevraagd, is `UnorderedNodeIterator` altijd het resulterende type. Elke andere representatie van een knooppuntset moet expliciet worden aangevraagd. |
| Number | `1` | Het resultaat is een getal zoals gedefinieerd in [XPath 1.0]. Documentwijziging maakt het getal niet ongeldig, maar kan betekenen dat her-evaluatie niet hetzelfde getal oplevert. |
| String | `2` | Het resultaat is een tekenreeks zoals gedefinieerd in [XPath 1.0]. Documentwijziging maakt de tekenreeks niet ongeldig, maar kan betekenen dat de tekenreeks niet langer overeenkomt met het huidige document. |
| Boolean | `3` | Het resultaat is een boolean zoals gedefinieerd in [XPath 1.0]. Documentwijziging maakt de boolean niet ongeldig, maar kan betekenen dat her-evaluatie niet dezelfde boolean oplevert. |
| UnorderedNodeIterator | `4` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die iteratief wordt benaderd, wat kan betekenen dat knooppunten niet in een specifieke volgorde worden geproduceerd. Documentwijziging maakt de iteratie ongeldig. Dit is het standaardtype dat wordt geretourneerd als het resultaat een knooppuntset is en het type `Any` wordt aangevraagd. |
| OrderedNodeIterator | `5` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die iteratief wordt benaderd en documentgeordende knooppunten produceert. Documentwijziging maakt de iteratie ongeldig. |
| UnorderedNodeSnapshot | `6` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die wordt benaderd als een snapshotlijst van knooppunten die mogelijk niet in een specifieke volgorde staan. Documentwijziging maakt de snapshot niet ongeldig, maar kan betekenen dat her-evaluatie niet dezelfde snapshot oplevert en knooppunten in de snapshot mogelijk zijn gewijzigd, verplaatst of verwijderd uit het document. |
| OrderedNodeSnapshot | `7` | Het resultaat is een knooppuntset zoals gedefinieerd in [XPath 1.0] die wordt benaderd als een snapshotlijst van knooppunten die in de oorspronkelijke documentvolgorde staan. Documentwijziging maakt de snapshot niet ongeldig, maar kan betekenen dat her-evaluatie niet dezelfde snapshot oplevert en knooppunten in de snapshot mogelijk zijn gewijzigd, verplaatst of verwijderd uit het document. |
| AnyUnorderedNode | `8` | Het resultaat is een knoopset zoals gedefinieerd door [XPath 1.0] en zal worden benaderd als een enkele knoop, die `null` kan zijn als de knoopset leeg is. Documentwijzigingen maken de knoop niet ongeldig, maar kunnen betekenen dat de resultaatsknoop niet langer overeenkomt met het huidige document. Dit is een gemak dat optimalisatie mogelijk maakt omdat de implementatie kan stoppen zodra een willekeurige knoop in de resulterende set is gevonden. Als er meer dan één knoop in het daadwerkelijke resultaat is, is de enkele teruggegeven knoop mogelijk niet de eerste in documentvolgorde. |
| FirstOrderedNode | `9` | Het resultaat is een knoopset zoals gedefinieerd door [XPath 1.0] en zal worden benaderd als een enkele knoop, die `null` kan zijn als de knoopset leeg is. Documentwijzigingen maken de knoop niet ongeldig, maar kunnen betekenen dat de resultaatsknoop niet langer overeenkomt met het huidige document. Dit is een gemak dat optimalisatie mogelijk maakt omdat de implementatie kan stoppen zodra de eerste knoop in documentvolgorde van de resulterende set is gevonden. Als er meer dan één knoop in het daadwerkelijke resultaat is, zal de enkele teruggegeven knoop de eerste in documentvolgorde zijn. |

### Zie ook

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
