---
title: "SVGMatrix-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.DataTypes.SVGMatrix Klasse. Viele der Grafikoperationen von SVG verwenden 2x3-Matrizen der Form a c e b d f, die bei Erweiterung zu einer 3x3-Matrix für matrixarithmetische Zwecke zu a c e b d f 0 0 1 werden."
type: docs
weight: 2230
url: /de/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Viele der Grafikoperationen von SVG verwenden 2x3-Matrizen der Form: [a c e] [b d f], die bei Erweiterung zu einer 3x3-Matrix für matrixarithmetische Zwecke werden: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | Die A-Komponente der Matrix. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | Die B-Komponente der Matrix. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | Die C-Komponente der Matrix. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | Die D-Komponente der Matrix. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | Die E-Komponente der Matrix. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | Die F-Komponente der Matrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(*SVGMatrix*) | Führt Matrixmultiplikation durch. Diese Matrix wird post-multipliziert mit einer anderen Matrix, wobei die resultierende neue Matrix zurückgegeben wird. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(*float*) | Post-multipliziert eine Rotations-Transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(*float*) | Post-multipliziert eine einheitliche Skalierungs-Transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(*float, float*) | Post-multipliziert eine nicht einheitliche Skalierungs-Transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(*float*) | Post-multipliziert eine SkewX-Transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(*float*) | Post-multipliziert eine SkewY-Transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(*float, float*) | Post-multipliziert eine Translations-Transformation auf die aktuelle Matrix und gibt die resultierende Matrix zurück. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
