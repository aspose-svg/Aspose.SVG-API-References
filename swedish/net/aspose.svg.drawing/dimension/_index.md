---
title: "Dimension-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Drawing.Dimension-klass. Tillhandahåller basklassen för dimensioner. Den allmänna termen dimension avser ett tal med en enhet kopplad till det och betecknas av UnitType"
type: docs
weight: 3410
url: /sv/net/aspose.svg.drawing/dimension/
---
## Dimension class

Tillhandahåller basklassen för dimensioner. Den allmänna termen 'dimension' avser ett tal med en enhet kopplad till det, och betecknas av [`UnitType`](../unittype/).

```csharp
public abstract class Dimension : Numeric
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | Hämtar enhetstypen för [`Unit`](../unit/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller hamnar i samma position i sorteringsordningen som det andra objektet. |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | Bestämmer om det angivna objektet är lika med den här instansen. |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | Avgör om den angivna [`Unit`](../unit/), är lika med denna instans. |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | Returnerar en hashkod för den här instansen. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | Hämtar enhetsvärdet. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | Hämtar värdet konverterat till den angivna [`UnitType`](../unittype/). |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | Returnerar en sträng som representerar den här instansen. |

### Se även

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
