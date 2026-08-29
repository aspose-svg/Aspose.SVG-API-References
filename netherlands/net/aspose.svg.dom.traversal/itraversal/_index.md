---
title: "ITraversal-interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.ITraversal interface. Iterators worden gebruikt om door een verzameling nodes te stappen, bijvoorbeeld de verzameling nodes in een NodeList, de document-subboom beheerd door een bepaalde Node, de resultaten van een query of elke andere verzameling nodes. De verzameling nodes die moet worden geïtereerd wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde-traversal van een document-subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator aan te roepen."
type: docs
weight: 3260
url: /nl/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Iterators worden gebruikt om door een verzameling knopen te stappen, bijvoorbeeld de verzameling knopen in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor document‑volgorde traversie van een document‑subboom. Exemplaren van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | De NodeFilter die wordt gebruikt om nodes te filteren. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | De rootnode van de NodeIterator, zoals gespecificeerd toen deze werd aangemaakt. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | Dit attribuut bepaalt welke node-types worden gepresenteerd via de iterator. De beschikbare set constanten is gedefinieerd in de NodeFilter-interface. Nodes die niet worden geaccepteerd door whatToShow worden overgeslagen, maar hun kinderen kunnen nog steeds worden beschouwd. Merk op dat deze overslag voorrang heeft boven het filter, indien aanwezig. |

### Zie ook

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
