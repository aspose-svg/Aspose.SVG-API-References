---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.SVG för .NET API-referens"
description: "IDocumentTraversal CreateNodeIterator-metod. Skapa en ny NodeIterator över delträdet som har den angivna noden som rot."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/)*) {#createnodeiterator}

Skapa en ny NodeIterator över delträdet som har den angivna noden som rot.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att itereras tillsammans med sina barn. Iteratören är initialt placerad precis före denna nod. whatToShow-flaggorna och filtret, om något, beaktas inte när denna position sätts. Roten får inte vara null. |

### Returvärde

Den nyss skapade NodeIteratorn.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long*) {#createnodeiterator_1}

Skapa en ny NodeIterator över delträdet som har den angivna noden som rot.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att itereras tillsammans med sina barn. Iteratören är initialt placerad precis före denna nod. whatToShow-flaggorna och filtret, om något, beaktas inte när denna position sätts. Roten får inte vara null. |
| whatToShow | Int64 | flaggan specificerar vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av iteratören. Se beskrivningen av NodeFilter för mängden möjliga SHOW_ värden. Dessa flaggor kan kombineras med OR. |

### Returvärde

Den nyss skapade NodeIteratorn.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createnodeiterator_2}

Skapa en ny NodeIterator över delträdet som har den angivna noden som rot.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att itereras tillsammans med sina barn. Iteratören är initialt placerad precis före denna nod. whatToShow-flaggorna och filtret, om något, beaktas inte när denna position sätts. Roten får inte vara null. |
| whatToShow | Int64 | flaggan specificerar vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av iteratören. Se beskrivningen av NodeFilter för mängden möjliga SHOW_ värden. Dessa flaggor kan kombineras med OR. |
| filter | INodeFilter | NodeFilter att använda med denna TreeWalker, eller null för att indikera inget filter. |

### Returvärde

Den nyss skapade NodeIteratorn.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
