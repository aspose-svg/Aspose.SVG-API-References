---
title: "SVGMatrix klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.DataTypes.SVGMatrix klass. Många av SVG:s grafikoperationer använder 2x3-matriser av formen a c e b d f som när de expanderas till en 3x3-matris för matrisaritmetik blir a c e b d f 0 0 1."
type: docs
weight: 2230
url: /sv/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Många av SVG:s grafikoperationer använder 2x3‑matriser av formen: [a c e] [b d f] som, när de expanderas till en 3x3‑matris för matrisaritmetik, blir: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | A-komponenten i matrisen. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | B-komponenten i matrisen. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | C-komponenten i matrisen. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | D-komponenten i matrisen. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | E-komponenten i matrisen. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | F-komponenten i matrisen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | Utför matris‑multiplikation. Denna matris multipliceras post‑multiplikativt med en annan matris och returnerar den resulterande nya matrisen. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | Post‑multiplicerar en rotations‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | Post‑multiplicerar en enhetlig skalförändring på den aktuella matrisen och returnerar den resulterande matrisen. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | Post‑multiplicerar en icke‑enhetlig skalförändring på den aktuella matrisen och returnerar den resulterande matrisen. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | Post‑multiplicerar en skewX‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | Post‑multiplicerar en skewY‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | Returnerar en sträng som representerar den här instansen. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | Post‑multiplicerar en translations‑transformation på den aktuella matrisen och returnerar den resulterande matrisen. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
