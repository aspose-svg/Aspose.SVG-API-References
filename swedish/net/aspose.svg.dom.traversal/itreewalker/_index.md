---
title: "ITreeWalker-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal.ITreeWalker interface. TreeWalker-objekt används för att navigera i ett dokumentträd eller underträd med den vy av dokumentet som definieras av deras whatToShow-flaggor och eventuellt filter. Alla funktioner som utför navigation med en TreeWalker kommer automatiskt att stödja vilken vy som helst som definieras av en TreeWalker."
type: docs
weight: 3270
url: /sv/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker‑objekt används för att navigera i ett dokumentträd eller en undernod med hjälp av dokumentvyn som definieras av deras whatToShow‑flaggor och filter (om sådant finns). Alla funktioner som utför navigering med en TreeWalker kommer automatiskt att stödja vilken vy som helst som definieras av en TreeWalker.

Att utelämna noder från den logiska vyn av ett underträd kan leda till en struktur som är avsevärt annorlunda än samma underträd i det kompletta, ofiltrerade dokumentet. Noder som är syskon i TreeWalker‑vyn kan vara barn till olika, vida åtskilda noder i den ursprungliga vyn. Till exempel, överväg ett NodeFilter som hoppar över alla noder förutom Text‑noder och rotnoden i ett dokument. I den logiska vyn som resultat blir alla textnoder syskon och visas som direkta barn till rotnoden, oavsett hur djupt den ursprungliga dokumentstrukturen är inbäddad.

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | Noden där TreeWalker för närvarande är placerad. Ändringar i DOM‑trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också explicit sättas till vilken nod som helst, oavsett om den ligger inom underträdet som specificerats av rotnoden eller skulle accepteras av filtret och whatToShow‑flaggorna. Ytterligare traversering sker relativt till currentNode även om den inte är en del av den aktuella vyn, genom att tillämpa filtren i den begärda riktningen; om ingen traversering är möjlig ändras inte currentNode. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | Flyttar TreeWalker till det första synliga barnet till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har några synliga barn returneras null och den aktuella noden behålls. |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | Flyttar TreeWalker till det sista synliga barnet till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har synliga barn returneras null och den aktuella noden behålls. |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | Flyttar TreeWalker till nästa synliga nod i dokumentordning relativt den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har någon nästa nod, eller om sökningen efter nextNode försöker gå uppåt från TreeWalkers rotnod, returneras null och den aktuella noden behålls. |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | Flyttar TreeWalker till nästa syskon till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har något synligt nästa syskon returneras null och den aktuella noden behålls. |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | Flyttar till och returnerar den närmaste synliga föräldranoden till den aktuella noden. Om sökningen efter parentNode försöker gå uppåt från TreeWalkers rotnod, eller om den misslyckas med att hitta en synlig föräldranod, behåller denna metod den aktuella positionen och returnerar null. |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | Flyttar TreeWalker till föregående synliga nod i dokumentordning relativt den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har någon föregående nod, eller om sökningen efter previousNode försöker gå uppåt från TreeWalkers rotnod, returneras null och den aktuella noden behålls. |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | Flyttar TreeWalker till föregående syskon till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har något synligt föregående syskon returneras null och den aktuella noden behålls. |

### Se även

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
