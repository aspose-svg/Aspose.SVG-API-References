---
title: "Node.CloneNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node CloneNode-metod. Returnerar en duplikat av noden som metoden anropades på."
type: docs
weight: 180
url: /sv/net/aspose.svg.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Returnerar en kopia av den nod som denna metod anropades på.

Att klona en nod kopierar alla dess attribut och deras värden, inklusive inbyggda (inline) lyssnare. Den kopierar inte händelselyssnare som lagts till med [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) eller de som tilldelats elementegenskaper (t.ex. node.onclick = someFunction). Dessutom kopieras den målade bilden inte för ett HTMLCanvasElement-element.

```csharp
public Node CloneNode()
```

### Returvärde

Den nya [`Node`](../) klonad. Den klonade noden har ingen förälder och är inte en del av dokumentet förrän den läggs till i en annan nod som är en del av dokumentet, med hjälp av [`AppendChild`](../appendchild/) eller en liknande metod.

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CloneNode(*bool*) {#clonenode_1}

Returnerar en kopia av den nod som denna metod anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte.

Att klona en nod kopierar alla dess attribut och deras värden, inklusive inbyggda (inline) lyssnare. Den kopierar inte händelselyssnare som lagts till med [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) eller de som tilldelats elementegenskaper (t.ex. node.onclick = someFunction). Dessutom kopieras den målade bilden inte för ett HTMLCanvasElement-element.

```csharp
public Node CloneNode(bool deep)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | Boolean | Om sant, kopieras noden och hela dess underträd, inklusive text som kan finnas i barn-`[`Text`](../../text/)`-noder, också. |

### Returvärde

Den nya [`Node`](../) klonad. Den klonade noden har ingen förälder och är inte en del av dokumentet förrän den läggs till i en annan nod som är en del av dokumentet, med hjälp av [`AppendChild`](../appendchild/) eller en liknande metod.

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
