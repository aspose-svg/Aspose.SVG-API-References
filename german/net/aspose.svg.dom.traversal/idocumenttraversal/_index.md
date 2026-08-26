---
title: "IDocumentTraversal Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Traversal.IDocumentTraversal Schnittstelle. DocumentTraversal enthält Methoden, die Iteratoren und tree-walkers erstellen, um einen Knoten und seine Kinder in Dokumentreihenfolge depth first pre-order Traversal zu durchlaufen, was der Reihenfolge entspricht, in der die Start‑Tags in der Textdarstellung des Dokuments vorkommen. In DOMs, die das Traversal‑Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document‑Interface implementieren."
type: docs
weight: 3220
url: /de/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contains methods that create iterators and tree-walkers to traverse a node and its children in document order (depth first, pre-order traversal, which is equivalent to the order in which the start tags occur in the text representation of the document). In DOMs which support the Traversal feature, DocumentTraversal will be implemented by the same objects that implement the Document interface.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
