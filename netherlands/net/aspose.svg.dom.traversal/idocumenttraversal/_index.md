---
title: "IDocumentTraversal Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.IDocumentTraversal interface. DocumentTraversal bevat methoden die iterators en tree-walkers maken om een knooppunt en zijn kinderen te doorlopen in documentvolgorde, diepte-eerst pre-order traversals, wat overeenkomt met de volgorde waarin de starttags voorkomen in de tekstrepresentatie van het document. In DOM's die de Traversal-functie ondersteunen, wordt DocumentTraversal geïmplementeerd door dezelfde objecten die de Document-interface implementeren."
type: docs
weight: 3220
url: /nl/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal bevat methoden die iterators en tree‑walkers maken om een knoop en zijn kinderen in documentvolgorde te doorlopen (diepte‑eerste, pre‑order traversie, wat overeenkomt met de volgorde waarin de start‑tags voorkomen in de tekstrepresentatie van het document). In DOM’s die de Traversal‑functie ondersteunen, wordt DocumentTraversal geïmplementeerd door dezelfde objecten die de Document‑interface implementeren.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Maak een nieuwe NodeIterator aan over de subboom die is geworteld in het opgegeven knooppunt. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij de opgegeven knoop. |

### Zie ook

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
