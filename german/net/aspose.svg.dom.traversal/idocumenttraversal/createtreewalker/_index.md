---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.SVG für .NET-API-Referenz
description: IDocumentTraversal methode. Erstellen Sie einen neuen TreeWalker über dem Teilbaum der an dem angegebenen Knoten verwurzelt ist.
type: docs
weight: 20
url: /de/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Erstellen Sie einen neuen TreeWalker über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der als Wurzel für the TreeWalker dienen wird. Die whatToShow-Flags und der NodeFilter werden beim Festlegen dieses Werts nicht berücksichtigt; jeder Knotentyp wird als Root akzeptiert. Der aktuelle Knoten des TreeWalkers wird mit diesem Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die -Wurzel fungiert als Haltepunkt für Traversal -Methoden, die in der Dokumentstruktur nach oben schauen, wie z. B. parentNode und nextNode. Die Wurzel muss nicht null sein. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../idocumenttraversal/)
* Montage [Aspose.SVG](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Erstellen Sie einen neuen TreeWalker über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der als Wurzel für the TreeWalker dienen wird. Die whatToShow-Flags und der NodeFilter werden beim Festlegen dieses Werts nicht berücksichtigt; jeder Knotentyp wird als Root akzeptiert. Der aktuelle Knoten des TreeWalkers wird mit diesem Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die -Wurzel fungiert als Haltepunkt für Traversal -Methoden, die in der Dokumentstruktur nach oben schauen, wie z. B. parentNode und nextNode. Die Wurzel muss nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des Baums erscheinen können, der vom Tree-Walker präsentiert wird. Siehe die Beschreibung von NodeFilter für den Satz möglicher SHOW_ Werte. Diese Flags können mit ODER kombiniert werden. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../idocumenttraversal/)
* Montage [Aspose.SVG](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Erstellen Sie einen neuen TreeWalker über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der als Wurzel für the TreeWalker dienen wird. Die whatToShow-Flags und der NodeFilter werden beim Festlegen dieses Werts nicht berücksichtigt; jeder Knotentyp wird als Root akzeptiert. Der aktuelle Knoten des TreeWalkers wird mit diesem Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die -Wurzel fungiert als Haltepunkt für Traversal -Methoden, die in der Dokumentstruktur nach oben schauen, wie z. B. parentNode und nextNode. Die Wurzel muss nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des Baums erscheinen können, der vom Tree-Walker präsentiert wird. Siehe die Beschreibung von NodeFilter für den Satz möglicher SHOW_ Werte. Diese Flags können mit ODER kombiniert werden. |
| filter | INodeFilter | NodeFilter, der mit this TreeWalker verwendet werden soll, oder null, um anzugeben, dass kein Filter vorhanden ist. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../idocumenttraversal/)
* Montage [Aspose.SVG](../../../)


