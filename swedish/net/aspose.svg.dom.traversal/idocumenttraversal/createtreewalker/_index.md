---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.SVG för .NET API-referens"
description: "IDocumentTraversal CreateTreeWalker-metoden. Skapa en ny TreeWalker över delträdet som har den angivna noden som rot"
type: docs
weight: 20
url: /sv/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

Skapa en ny TreeWalker över delträdet som har den angivna noden som rot.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow‑flaggorna och NodeFilter beaktas inte när detta värde sätts; alla nodtyper accepteras som rot. currentNode för TreeWalker initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som söker uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |

### Returvärde

Den nyss skapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

Skapa en ny TreeWalker över delträdet som har den angivna noden som rot.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow‑flaggorna och NodeFilter beaktas inte när detta värde sätts; alla nodtyper accepteras som rot. currentNode för TreeWalker initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som söker uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |
| whatToShow | Int64 | flag specificerar vilka nodtyper som kan visas i det logiska trädet som presenteras av tree-walkern. Se beskrivningen av NodeFilter för mängden möjliga SHOW_-värden. Dessa flaggor kan kombineras med OR. |

### Returvärde

Den nyss skapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

Skapa en ny TreeWalker över delträdet som har den angivna noden som rot.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow‑flaggorna och NodeFilter beaktas inte när detta värde sätts; alla nodtyper accepteras som rot. currentNode för TreeWalker initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som söker uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |
| whatToShow | Int64 | flag specificerar vilka nodtyper som kan visas i det logiska trädet som presenteras av tree-walkern. Se beskrivningen av NodeFilter för mängden möjliga SHOW_-värden. Dessa flaggor kan kombineras med OR. |
| filter | INodeFilter | NodeFilter att använda med denna TreeWalker, eller null för att indikera inget filter. |

### Returvärde

Den nyss skapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
