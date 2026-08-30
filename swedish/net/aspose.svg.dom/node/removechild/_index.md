---
title: "Node.RemoveChild"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node RemoveChild‑metod. Tar bort en barnnod från DOM och returnerar den borttagna noden"
type: docs
weight: 270
url: /sv/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

Tar bort en barnnod från DOM och returnerar den borttagna noden.

Obs: Så länge en referens hålls till den borttagna barnet, finns den fortfarande i minnet, men är inte längre en del av DOM. Den kan fortfarande återanvändas senare i koden. Om returvärdet från `RemoveChild` inte lagras och ingen annan referens hålls, kommer det automatiskt att tas bort från minnet efter en kort tid.

```csharp
public Node RemoveChild(Node child)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| child | Node | Ett [`Node`](../) som är barnnoden som ska tas bort från DOM. |

### Returvärde

Till skillnad från [`CloneNode`](../clonenode/) bevarar returvärdet de [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/)‑objekt som är associerade med det.

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
