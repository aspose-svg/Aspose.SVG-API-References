---
title: "HTMLCollection Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Collections.HTMLCollection class. De HTMLCollection vertegenwoordigt een algemene verzameling van Element"
type: docs
weight: 2010
url: /nl/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

De `HTMLCollection` vertegenwoordigt een algemene verzameling van [`Element`](../../aspose.svg.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | Retourneert het index‑de item in de collectie. Als index groter dan of gelijk is aan het aantal knooppunten in de lijst, retourneert dit null. |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | Het aantal knooppunten in de lijst. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | Verkrijgt de enumerator. |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | Retourneert het item in de collectie dat overeenkomt met de opgegeven naam. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
