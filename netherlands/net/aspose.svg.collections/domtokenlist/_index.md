---
title: "DOMTokenList Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Collections.DOMTokenList class. De DOMTokenList-klasse vertegenwoordigt een set van door spaties gescheiden tokens. Het wordt geïndexeerd beginnend bij 0, net als JavaScript Array-objecten. DOMTokenList is altijd hoofdlettergevoelig."
type: docs
weight: 2000
url: /nl/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

De DOMTokenList‑klasse vertegenwoordigt een set van door spaties gescheiden tokens. Het is geïndexeerd vanaf 0, net als JavaScript‑arrayobjecten. DOMTokenList is altijd hoofdlettergevoelig.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | Retourneert het item in de lijst op basis van zijn index, of null als de index groter dan of gelijk is aan de lengte van de lijst. |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | Retourneert een ulong die het aantal tokens in deze lijst vertegenwoordigt. |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | Haalt de waarde van een overeenkomstig attribuut op of stelt deze in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | Voegt de opgegeven token(s) toe aan de lijst. |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | Retourneert true als de lijst de opgegeven token bevat, anders false. |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | Retourneert een enumerator die door de collectie iterereert. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | Verwijdert de opgegeven token(s) uit de lijst. |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | Vervangt een bestaande token door een nieuwe token. Doet niets als de eerste token niet bestaat. |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | Retourneert true als een gegeven token voorkomt in de ondersteunde tokens van het bijbehorende attribuut. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | Verwijdert de token uit de lijst als deze bestaat, of voegt de token toe aan de lijst als deze niet bestaat. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | Verwijdert de token uit de lijst als deze bestaat, of voegt de token toe aan de lijst als deze niet bestaat. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
