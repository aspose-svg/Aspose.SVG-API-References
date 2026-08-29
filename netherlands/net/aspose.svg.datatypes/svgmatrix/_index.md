---
title: "SVGMatrix Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.DataTypes.SVGMatrix class. Veel van de grafische bewerkingen van SVG's gebruiken 2x3-matrices van de vorm a c e b d f die, wanneer ze worden uitgebreid tot een 3x3-matrix voor matrixrekenkunde, worden a c e b d f 0 0 1."
type: docs
weight: 2230
url: /nl/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Veel van de grafische bewerkingen van SVG gebruiken 2x3‑matrices van de vorm: [a c e] [b d f] die, wanneer uitgebreid tot een 3x3‑matrix voor matrixrekenkunde, worden: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | Het A-component van de matrix. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | Het B-component van de matrix. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | Het C-component van de matrix. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | Het D-component van de matrix. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | Het E-component van de matrix. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | Het F-component van de matrix. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Vrijgeeft niet‑beheerde en - optioneel - beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | Voert matrixvermenigvuldiging uit. Deze matrix wordt post-multiplied met een andere matrix, waardoor de resulterende nieuwe matrix wordt teruggegeven. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | Post-multiplieert een rotatie-transformatie op de huidige matrix en retourneert de resulterende matrix. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | Post-multiplieert een uniforme schaaltransformatie op de huidige matrix en retourneert de resulterende matrix. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | Voegt een niet-uniforme schaaltransformatie post-multiplicatief toe aan de huidige matrix en retourneert de resulterende matrix. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | Voegt een skewX-transformatie post-multiplicatief toe aan de huidige matrix en retourneert de resulterende matrix. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | Voegt een skewY-transformatie post-multiplicatief toe aan de huidige matrix en retourneert de resulterende matrix. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | Voegt een translatie-transformatie post-multiplicatief toe aan de huidige matrix en retourneert de resulterende matrix. |

### Zie ook

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
