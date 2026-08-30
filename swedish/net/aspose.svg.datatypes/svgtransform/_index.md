---
title: "SVGTransform-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.DataTypes.SVGTransform-klass. SVGTransform är gränssnittet för en av komponenttransformeringarna inom en SVGTransformList, så ett SVGTransform-objekt motsvarar en enskild komponent, t.ex. skala eller matris, inom en transformattributspecifikation"
type: docs
weight: 2310
url: /sv/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform är gränssnittet för en av komponenttransformationerna inom en SVGTransformList; därmed motsvarar ett SVGTransform‑objekt en enskild komponent (t.ex. 'scale(…)' eller 'matrix(…)') inom en ‘transform’-attributspecifikation.

```csharp
public class SVGTransform : SVGValueType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | Ett bekvämt attribut för SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY. Det lagrar den angivna vinkeln. För SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE och SVG_TRANSFORM_SCALE kommer vinkeln att vara noll. |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | Matrisen som representerar denna transformation. Matrisobjektet är levande, vilket betyder att alla ändringar som görs på SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt (dvs. utan att använda metoderna på SVGTransform‑gränssnittet) ändras typen på SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen värdena a, b, c, d, e, f som tillhandahålls av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f translationsvärdena (a=1, b=0, c=0 och d=1). För SVG_TRANSFORM_SCALE representerar a och d skalningsvärdena (b=0, c=0, e=0 och f=0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som ger den angivna skevningen (e=0 och f=0). För SVG_TRANSFORM_ROTATE representerar a, b, c, d, e och f tillsammans matrisen som ger den angivna rotationen. När rotationen är kring centrumpunkten (0, 0) blir e och f noll. |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | Typen av värdet enligt en av SVG_TRANSFORM_*-konstanterna som definieras på detta gränssnitt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | Ställer in transformtyp till SVG_TRANSFORM_MATRIX med parametern matrix som definierar den nya transformationen. Värdena från parameter‑matrixen kopieras; matrix‑parametern ersätter inte SVGTransform::matrix. |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | Ställer in transformtyp till SVG_TRANSFORM_ROTATE med parametern angle som definierar rotationsvinkeln och parametrarna cx och cy som definierar det valfria rotationscentrumet. |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | Ställer in transformtyp till SVG_TRANSFORM_SCALE med parametrarna sx och sy som definierar skalningsvärdena. |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | Ställer in transformtyp till SVG_TRANSFORM_SKEWX med parametern angle som definierar mängden skevning. |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | Ställer in transformtyp till SVG_TRANSFORM_SKEWY med parametern angle som definierar mängden skevning. |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | Ställer in transformtyp till SVG_TRANSFORM_TRANSLATE med parametrarna tx och ty som definierar translationsvärdena. |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | Returnerar en sträng som representerar den här instansen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | En 'matrix(…)'‑transformation. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | En 'rotate(…)'‑transformation. |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | En 'scale(…)' transformation. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | En 'skewX(…)' transformation. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | En 'skewY(…)' transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | En 'translate(…)' transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | Enhetstypen är inte en av de fördefinierade typerna. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka byta ett befintligt värde till denna typ. |

### Se även

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
