---
title: "Node.AppendChild"
second_title: "Aspose.SVG för .NET API-referens"
description: "Node AppendChild-metod. Lägger till en nod i slutet av listan av barn till en angiven föräldranod. Om det givna child är en referens till en befintlig nod i dokumentet flyttar AppendChild den från dess nuvarande position till den nya positionen; det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod."
type: docs
weight: 170
url: /sv/net/aspose.svg.dom/node/appendchild/
---
## Node.AppendChild method

Lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om den angivna barnet är en referens till en befintlig nod i dokumentet, flyttar `AppendChild` den från sin nuvarande position till den nya positionen (det krävs ingen borttagning av noden från dess föräldranod innan den läggs till i en annan nod).

Detta innebär att en nod inte kan finnas på två ställen i dokumentet samtidigt. Så om noden redan har en förälder tas noden först bort och sedan läggs till på den nya positionen. Metoden [`CloneNode`](../clonenode/) kan användas för att skapa en kopia av noden innan den läggs till under den nya föräldern. Kopior som görs med [`CloneNode`](../clonenode/) hålls inte automatiskt synkroniserade.

```csharp
public Node AppendChild(Node node)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nod | Node | Noden som ska läggas till i den angivna föräldranoden (vanligtvis ett element). |

### Returvärde

En nod som är det tillagda barnet, förutom när barnet är ett [`DocumentFragment`](../../documentfragment/), i vilket fall det tomma [`DocumentFragment`](../../documentfragment/) returneras.

### Undantag

| undantag | villkor |
| --- | --- |
| DOMException | Kastas när begränsningarna i DOM-trädet bryts. |

### Se även

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
