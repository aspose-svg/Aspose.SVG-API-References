---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "INodeFilter AcceptNode metod. Testar om en angiven nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. Du kan dock göra det om du vill använda samma filter för att styra din egen programlogik."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Testa om en specificerad nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. (Även om du kan göra det om du vill använda samma filter för att styra din egen programlogik.)

```csharp
public short AcceptNode(Node n)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| n | Node | nod att kontrollera för att se om den passerar filtret eller inte. |

### Returvärde

en konstant för att avgöra om noden accepteras, avvisas eller hoppas över, enligt definitionen ovan.

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
