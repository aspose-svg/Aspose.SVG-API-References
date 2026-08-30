---
title: "SVGTransform.Matrix"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGTransform Matrix-egenskapen. Matrisen som representerar denna transformation. Matrisobjektet är levande, vilket betyder att alla ändringar som görs på SVGTransform‑objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt, d.v.s. utan att använda metoderna på SVGTransform‑gränssnittet, ändras typen på SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen värdena a b c d e f som tillhandahålls av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f förflyttningsmängderna a 1 b 0 c 0 och d 1. För SVG_TRANSFORM_SCALE representerar a och d skalfaktorerna b 0 c 0 e 0 och f 0. För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a b c och d matrisen som ger den angivna skevheten 0 och f 0. För SVG_TRANSFORM_ROTATE representerar a b c d e och f tillsammans matrisen som ger den angivna rotationen. När rotationen är kring centrumpunkten 0 0 är e och f noll"
type: docs
weight: 20
url: /sv/net/aspose.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Matrisen som representerar denna transformation. Matrisobjektet är levande, vilket betyder att alla ändringar som görs på SVGTransform-objektet omedelbart återspeglas i matrisobjektet och vice versa. Om matrisobjektet ändras direkt (dvs. utan att använda metoderna på SVGTransform‑gränssnittet) ändras typen på SVGTransform till SVG_TRANSFORM_MATRIX. För SVG_TRANSFORM_MATRIX innehåller matrisen värdena a, b, c, d, e, f som tillhandahålls av användaren. För SVG_TRANSFORM_TRANSLATE representerar e och f translationsvärdena (a=1, b=0, c=0 och d=1). För SVG_TRANSFORM_SCALE representerar a och d skalningsvärdena (b=0, c=0, e=0 och f=0). För SVG_TRANSFORM_SKEWX och SVG_TRANSFORM_SKEWY representerar a, b, c och d matrisen som ger den angivna skevningen (e=0 och f=0). För SVG_TRANSFORM_ROTATE representerar a, b, c, d, e och f tillsammans matrisen som ger den angivna rotationen. När rotationen är kring centrumpunkten (0, 0) blir e och f noll.

```csharp
public SVGMatrix Matrix { get; }
```

### Property Value

Matrisen som representerar denna transformation.

### Se även

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
