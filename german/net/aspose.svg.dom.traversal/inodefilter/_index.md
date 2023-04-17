---
title: Interface INodeFilter
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Traversal.INodeFilter koppel. Filter sind Objekte die Knoten herausfiltern können. Wenn einem NodeIterator oder TreeWalker ein NodeFilter gegeben wird wendet er den Filter an bevor er den nächsten Knoten zurückgibt. Wenn der Filter sagt dass der Knoten akzeptiert werden soll gibt die Traversierungslogik it zurück Andernfalls sucht Traversal nach dem nächsten Knoten und gibt vor dass der zurückgewiesene Knoten nicht vorhanden war.
type: docs
weight: 1240
url: /de/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

Filter sind Objekte, die Knoten "herausfiltern" können. Wenn einem NodeIterator oder TreeWalker ein NodeFilter gegeben wird, wendet er den Filter an, bevor er den nächsten -Knoten zurückgibt. Wenn der Filter sagt, dass der Knoten akzeptiert werden soll, gibt die Traversierungslogik it zurück; Andernfalls sucht Traversal nach dem nächsten Knoten und gibt vor, dass der zurückgewiesene -Knoten nicht vorhanden war.

Das DOM bietet keine Filter. NodeFilter ist nur eine -Schnittstelle, die Benutzer implementieren können, um ihre eigenen Filter bereitzustellen.

NodeFilter müssen nicht wissen, wie sie von Knoten zu Knoten traversieren, noch müssen sie irgendetwas über die Datenstruktur wissen, die traversiert. Das macht es sehr einfach, Filter zu schreiben, da sie nur wissen müssen, wie man einen einzelnen Knoten auswertet. Ein -Filter kann mit einer Reihe verschiedener Arten von Durchläufen verwendet werden, fördert die Wiederverwendung von Code.

Siehe auch die[Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @seit DOM Level 2

```csharp
public interface INodeFilter
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode/)(Node) | Testet, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; es wird normalerweise nicht direkt von Benutzercode aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben -Filter verwenden wollten, um Ihre eigene Anwendungslogik zu steuern.) |

### Siehe auch

* namensraum [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* Montage [Aspose.SVG](../../)


