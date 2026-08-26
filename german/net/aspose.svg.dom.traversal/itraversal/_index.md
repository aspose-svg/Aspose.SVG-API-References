---
title: "ITraversal Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Traversal.ITraversal interface. Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, das Dokumentunterbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator-Implementierung für die dokumentreihenfolgebasierte Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden erstellt, indem DocumentTraversal .createNodeIterator aufgerufen wird."
type: docs
weight: 3260
url: /de/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Menge von Knoten. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die dokumentreihenfolge Traversierung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden erstellt, indem DocumentTraversal .createNodeIterator() aufgerufen wird.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | Der NodeFilter, der zum Filtern von Knoten verwendet wird. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | Der Wurzelknoten des NodeIterator, wie bei seiner Erstellung angegeben. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | Dieses Attribut bestimmt, welche Knotentypen über den Iterator präsentiert werden. Die verfügbare Menge an Konstanten ist im NodeFilter interface definiert. Knoten, die von whatToShow nicht akzeptiert werden, werden übersprungen, aber ihre Kinder können weiterhin berücksichtigt werden. Beachten Sie, dass dieses Überspringen Vorrang vor dem Filter hat, falls vorhanden. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
