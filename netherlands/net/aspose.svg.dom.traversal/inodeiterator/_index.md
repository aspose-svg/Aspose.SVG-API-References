---
title: "INodeIterator Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.INodeIterator interface. Iterators worden gebruikt om door een verzameling knooppunten te stappen, bijv. de verzameling knooppunten in een NodeList, de documentsubboom beheerd door een specifieke Node, de resultaten van een query of elke andere verzameling knooppunten. De te itereren verzameling wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde-traversal van een documentsubboom. Exemplaren van deze iterators worden gecreëerd door het aanroepen van DocumentTraversal .createNodeIterator"
type: docs
weight: 3250
url: /nl/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators worden gebruikt om door een verzameling knopen te stappen, bijvoorbeeld de verzameling knopen in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor document‑volgorde traversie van een document‑subboom. Exemplaren van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | De waarde van deze vlag bepaalt of de kinderen van entiteitsreferentieknooppunten zichtbaar zijn voor de iterator. Als false, worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft boven whatToShow en de filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knooppunten over te slaan. Om een weergave van het document te produceren waarin entiteitsreferenties zijn uitgebreid en het entiteitsreferentieknooppunt zelf niet wordt blootgesteld, gebruik de whatToShow vlaggen om het entiteitsreferentieknooppunt te verbergen en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave van het document te produceren met entiteitsreferentieknooppunten maar zonder entiteitsexpansie, gebruik de whatToShow vlaggen om het entiteitsreferentieknooppunt te tonen en stel expandEntityReferences in op false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | Het huidige referentieknooppunt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Koppelt de NodeIterator los van de set waarover hij heeft geïtereerd, maakt eventuele computationele bronnen vrij en plaatst de iterator in de INVALID state. Nadat detach is aangeroepen, zullen oproepen naar nextNode of previousNode de uitzondering INVALID_STATE_ERR veroorzaken. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Retourneert het volgende knooppunt in de set en verplaatst de positie van de iterator in de set vooruit. Nadat een NodeIterator is aangemaakt, retourneert de eerste oproep naar nextNode() het eerste knooppunt in de set. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Retourneert het vorige knooppunt in de set en verplaatst de positie van de NodeIterator achteruit in de set. |

### Zie ook

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
