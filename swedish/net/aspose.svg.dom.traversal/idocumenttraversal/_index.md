---
title: "IDocumentTraversal-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal.IDocumentTraversal-gränssnitt. DocumentTraversal innehåller metoder som skapar iteratorer och träd-walkers för att traversera en nod och dess barn i dokumentordning, djup‑först förordningstraversering, vilket motsvarar den ordning i vilken starttaggarna förekommer i dokumentets textrepresentation. I DOM‑er som stödjer Traversal‑funktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar Document‑gränssnittet."
type: docs
weight: 3220
url: /sv/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal innehåller metoder som skapar iteratorer och tree‑walkers för att traversera en nod och dess barn i dokumentordning (djup först, pre‑order‑traversering, vilket är ekvivalent med den ordning i vilken starttaggarna förekommer i dokumentets textrepresentation). I DOM‑er som stödjer Traversal‑funktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar Document‑gränssnittet.

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |

### Se även

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
