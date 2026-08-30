---
title: "Document.CreateNodeIterator"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document CreateNodeIterator metod. Skapa en ny NodeIterator över delträdet som har den angivna noden som rot"
type: docs
weight: 900
url: /sv/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
