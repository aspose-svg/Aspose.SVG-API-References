---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "NodeFilter AcceptNode-Methode. Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen und wird normalerweise nicht direkt aus dem Benutzercode heraus aufgerufen. Sie können dies jedoch tun, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Prüfen, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus Benutzercode aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern.)

```csharp
public abstract short AcceptNode(Node n)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| n | Node | Knoten, der überprüft werden soll, ob er den Filter besteht oder nicht. |

### Rückgabewert

Eine Konstante, um zu bestimmen, ob der Knoten akzeptiert, abgelehnt oder übersprungen wird, wie oben definiert.

### Siehe auch

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
