---
title: Interface ITraversal
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Traversal.ITraversal koppel. Iteratoren werden verwendet um schrittweise durch eine Menge von Knoten zu gehen z. B. die Menge von Knoten in einer NodeList den DokumentTeilbaum der von einem bestimmten Knoten gesteuert wird die Ergebnisse einer Abfrage oder irgendeine andere Menge von Knoten. Die Menge der zu iterierenden Knoten wird durch die Implementierung des NodeIterators bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIteratorImplementierung für die Dokumentreihenfolge Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden erstellt durch Aufrufen von DocumentTraversal .createNodeIterator.
type: docs
weight: 1260
url: /de/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Iteratoren werden verwendet, um schrittweise durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Knoten gesteuert wird, die Ergebnisse einer Abfrage oder irgendeine andere Menge von Knoten. Die Menge der zu iterierenden Knoten wird durch die -Implementierung des NodeIterators bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden erstellt durch Aufrufen von DocumentTraversal .createNodeIterator().

Siehe auch die[Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @seit DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | Der zum Screening von Knoten verwendete NodeFilter. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | Der Stammknoten des NodeIterators, wie angegeben, als er erstellt wurde. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | Dieses Attribut bestimmt, welche Knotentypen über den Iterator präsentiert werden. Der verfügbare Satz von Konstanten ist in der NodeFilter-Schnittstelle definiert. Knoten, die von whatToShow nicht akzeptiert werden, werden übersprungen, aber ihre Kinder können immer noch berücksichtigt werden. Beachten Sie, dass dieses Überspringen Vorrang vor dem Filter hat, falls vorhanden. |

### Siehe auch

* namensraum [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* Montage [Aspose.SVG](../../)


