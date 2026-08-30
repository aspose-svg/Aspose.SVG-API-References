---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "NodeFilter AcceptNode-metod. Testa om en specificerad nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. Du kan dock göra det om du vill använda samma filter för att styra din egen applikationslogik"
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Testa om en specificerad nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. (Även om du kan göra det om du vill använda samma filter för att styra din egen programlogik.)

```csharp
public abstract short AcceptNode(Node n)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| n | Node | nod att kontrollera för att se om den passerar filtret eller inte. |

### Returvärde

en konstant för att avgöra om noden accepteras, avvisas eller hoppas över, enligt definitionen ovan.

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
