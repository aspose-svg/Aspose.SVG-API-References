---
title: "SVGPoint klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.DataTypes.SVGPoint klass. Många av SVG‑DOM‑gränssnitten refererar till objekt av klassen SVGPoint. En SVGPoint är ett x‑y‑koordinatpar. När den används i matrisoperationer behandlas en SVGPoint som en vektor av formen x y 1. Om ett SVGRect‑objekt är markerat som skrivskyddat kommer ett försök att tilldela ett av dess attribut att resultera i ett undantag."
type: docs
weight: 2260
url: /sv/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

Många av SVG DOM-gränssnitten refererar till objekt av klassen SVGPoint. En SVGPoint är ett (x, y)-koordinatpar. När den används i matrisoperationer behandlas en SVGPoint som en vektor i formen: [x] [y] [1] Om ett SVGRect-objekt är markerat som skrivskyddat, kommer ett försök att tilldela ett av dess attribut att resultera i ett undantag.

```csharp
public class SVGPoint : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | X‑koordinaten. |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | Y‑koordinaten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | Tillämpar en 2×3‑matristransformation på detta SVGPoint‑objekt och returnerar ett nytt, transformerat SVGPoint‑objekt: newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | Returnerar en sträng som representerar den här instansen. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
