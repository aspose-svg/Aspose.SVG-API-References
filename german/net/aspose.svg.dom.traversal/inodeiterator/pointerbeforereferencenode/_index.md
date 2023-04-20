---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.SVG für .NET-API-Referenz
description: INodeIterator eigendom. Der Wert dieses Flags bestimmt ob die untergeordneten Referenzknoten von entity für den Iterator sichtbar sind. Wenn falsch werden sie und ihre Nachkommen zurückgewiesen. Beachten Sie dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Beachten Sie auch  dass dies derzeit die einzige Situation ist in der NodeIterators einen vollständigen Teilbaum ablehnen können anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erstellen die Entitätsreferenzen erweitert hat und den Entitätsreferenzknoten selbst nicht verfügbar macht verwenden Sie die whatToShowFlags für Blenden Sie die Entitätsreferenz node aus und setzen Sie expandEntityReferences auf true wenn Sie den Iterator erstellen. Um eine Ansicht des Dokuments zu erstellen das Entitätsreferenz Knoten aber keine Entitätserweiterung enthält verwenden Sie whatToShow flags  um den Entitätsreferenzknoten anzuzeigen und setzen Sie expandEntityReferences auf false.
type: docs
weight: 10
url: /de/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Der Wert dieses Flags bestimmt, ob die untergeordneten Referenzknoten von entity für den Iterator sichtbar sind. Wenn falsch, werden sie und ihre Nachkommen zurückgewiesen. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Beachten Sie auch , dass dies derzeit die einzige Situation ist, in der NodeIterators einen vollständigen Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erstellen, die Entitätsreferenzen erweitert hat und den Entitätsreferenzknoten selbst nicht verfügbar macht, verwenden Sie die whatToShow-Flags für Blenden Sie die Entitätsreferenz node aus und setzen Sie expandEntityReferences auf true, wenn Sie den Iterator erstellen. Um eine Ansicht des Dokuments zu erstellen, das Entitätsreferenz -Knoten, aber keine Entitätserweiterung enthält, verwenden Sie whatToShow flags , um den Entitätsreferenzknoten anzuzeigen, und setzen Sie expandEntityReferences auf false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Eigentumswert

`WAHR`if [Entity-Referenzen erweitern]; ansonsten,`FALSCH` .

### Siehe auch

* interface [INodeIterator](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../inodeiterator/)
* Montage [Aspose.SVG](../../../)


