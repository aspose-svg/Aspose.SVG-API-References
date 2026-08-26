---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IDocumentTraversal CreateTreeWalker-Methode. Erstellt einen neuen TreeWalker über den Teilbaum, der an dem angegebenen Knoten verwurzelt ist."
type: docs
weight: 20
url: /de/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow‑Flags und der NodeFilter werden beim Setzen dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenbaum nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow‑Flags und der NodeFilter werden beim Setzen dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenbaum nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Das Flag gibt an, welche Knotentypen in der logischen Ansicht des vom TreeWalker präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow‑Flags und der NodeFilter werden beim Setzen dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenbaum nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Das Flag gibt an, welche Knotentypen in der logischen Ansicht des vom TreeWalker präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |
| filter | INodeFilter | NodeFilter, der mit diesem TreeWalker verwendet werden soll, oder null, um keinen Filter anzugeben. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
