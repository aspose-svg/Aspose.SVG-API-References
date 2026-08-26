---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "INodeFilter AcceptNode‑Methode. Prüft, ob ein angegebenes Knoten im logischen View eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus dem Benutzercode heraus aufgerufen. Sie könnten sie jedoch verwenden, wenn Sie denselben Filter zur Steuerung Ihrer Anwendungslogik einsetzen möchten."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Prüfen, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus Benutzercode aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern.)

```csharp
public short AcceptNode(Node n)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| n | Node | Knoten, der überprüft werden soll, ob er den Filter besteht oder nicht. |

### Rückgabewert

Eine Konstante, um zu bestimmen, ob der Knoten akzeptiert, abgelehnt oder übersprungen wird, wie oben definiert.

### Siehe auch

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
