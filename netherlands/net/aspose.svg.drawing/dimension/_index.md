---
title: "Dimension Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Drawing.Dimension klasse. Biedt de basisklasse voor dimensies. De algemene term dimensie verwijst naar een getal met een eenheid eraan gekoppeld en wordt aangeduid met UnitType."
type: docs
weight: 3410
url: /nl/net/aspose.svg.drawing/dimension/
---
## Dimension class

Biedt de basisklasse voor dimensies. De algemene term 'dimensie' verwijst naar een getal met een eenheid eraan gekoppeld, en wordt aangeduid door [`UnitType`](../unittype/).

```csharp
public abstract class Dimension : Numeric
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | Haalt het eenheidstype van de [`Unit`](../unit/) op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | Vergelijkt de huidige instantie met een ander object van hetzelfde type en retourneert een geheel getal dat aangeeft of de huidige instantie voorafgaat, volgt of zich op dezelfde positie in de sorteervolgorde bevindt als het andere object. |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | Bepaalt of de opgegeven [`Unit`](../unit/) gelijk is aan deze instantie. |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | Retourneert een hashcode voor deze instantie. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | Haalt de eenheidswaarde op. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | Haalt de waarde op, geconverteerd naar het opgegeven [`UnitType`](../unittype/). |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
