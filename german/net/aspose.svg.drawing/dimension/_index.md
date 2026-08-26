---
title: "Dimension Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Drawing.Dimension Klasse. Stellt die Basisklasse für Dimensionen bereit. Der allgemeine Begriff Dimension bezieht sich auf eine Zahl mit einer angehängten Einheit und wird durch UnitType bezeichnet."
type: docs
weight: 3410
url: /de/net/aspose.svg.drawing/dimension/
---
## Dimension class

Stellt die Basisklasse für Dimensionen bereit. Der allgemeine Begriff 'Dimension' bezieht sich auf eine Zahl mit einer angehängten Einheit und wird durch [`UnitType`](../unittype/) bezeichnet.

```csharp
public abstract class Dimension : Numeric
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | Ruft den Einheitstyp des [`Unit`](../unit/) ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt einen Integer zurück, der angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge liegt. |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | Bestimmt, ob das angegebene [`Unit`](../unit/) gleich dieser Instanz ist. |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | Ruft den Einheitswert ab. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | Ruft den Wert ab, der in den angegebenen [`UnitType`](../unittype/) konvertiert wurde. |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
