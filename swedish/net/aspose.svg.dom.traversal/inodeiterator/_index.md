---
title: "INodeIterator-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal.INodeIterator-gränssnitt. Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentets underträd som styrs av en viss Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementation för dokumentordningens traversering av ett dokumentunderträd. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal.createNodeIterator."
type: docs
weight: 3250
url: /sv/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentundernoden som styrs av en specifik Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordnings‑traversering av ett dokumentundernod. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Värdet på denna flagga bestämmer om barnen till entitetsreferensnoder är synliga för iteratorn. Om falskt kommer de och deras underordnade att avvisas. Observera att detta avvisande har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt underträd istället för att hoppa över enskilda noder. För att skapa en vy av dokumentet där entitetsreferenser är expanderade och där själva entitetsreferensnoden inte exponeras, använd whatToShow‑flaggorna för att dölja entitetsreferensnoden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet som har entitetsreferensnoder men ingen entitetsutvidgning, använd whatToShow‑flaggorna för att visa entitetsreferensnoden och sätt expandEntityReferences till false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | Den aktuella referensnoden. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Kopplar bort NodeIterator från den uppsättning den itererade över, frigör alla beräkningsresurser och placerar iteratorn i INVALID‑tillståndet. Efter att detach har anropats kommer anrop till nextNode eller previousNode att kasta undantaget INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Returnerar nästa nod i uppsättningen och avancerar iteratorns position i uppsättningen. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode() den första noden i uppsättningen. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Returnerar föregående nod i uppsättningen och flyttar NodeIterators position bakåt i uppsättningen. |

### Se även

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
