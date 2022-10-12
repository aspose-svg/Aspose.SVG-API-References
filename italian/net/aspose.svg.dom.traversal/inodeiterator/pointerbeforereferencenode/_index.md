---
title: PointerBeforeReferenceNode
second_title: Riferimento API Aspose.SVG per .NET
description: Il valore di questo flag determina se i figli dei nodi di riferimento entity sono visibili alliteratore. Se false loro e i loro discendenti saranno rifiutati. Nota che questo rifiuto ha la precedenza su whatToShow e il filtro. Nota inoltre che questa è attualmente lunica situazione in cui NodeIterators può rifiutare un sottoalbero completo invece di saltare i singoli nodi. Per produrre una vista del documento che ha riferimenti a entità espansi e non espone il nodo di riferimento a entità stesso usa i flag whatToShow a nascondere il riferimento allentità node e impostare expandEntityReferences su true durante la creazione delliteratore . Per produrre una vista del documento che ha nodi entità reference ma nessuna espansione entità usa whatToShow flags per mostrare il nodo di riferimento entità e imposta expandEntityReferences su false.
type: docs
weight: 10
url: /it/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Il valore di questo flag determina se i figli dei nodi di riferimento entity sono visibili all'iteratore. Se false, loro e i loro discendenti saranno rifiutati. Nota che questo rifiuto ha la precedenza su whatToShow e il filtro. Nota inoltre che questa è attualmente l'unica situazione in cui NodeIterators può rifiutare un sottoalbero completo invece di saltare i singoli nodi. Per produrre una vista del documento che ha riferimenti a entità espansi e non espone il nodo di riferimento a entità stesso, usa i flag whatToShow a nascondere il riferimento all'entità node e impostare expandEntityReferences su true durante la creazione dell'iteratore . Per produrre una vista del documento che ha nodi entità reference ma nessuna espansione entità, usa whatToShow flags per mostrare il nodo di riferimento entità e imposta expandEntityReferences su false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Valore della proprietà

`VERO`if [espandi i riferimenti di entità]; altrimenti,`falso` .

### Guarda anche

* interface [INodeIterator](../../inodeiterator)
* spazio dei nomi [Aspose.Svg.Dom.Traversal](../../inodeiterator)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->