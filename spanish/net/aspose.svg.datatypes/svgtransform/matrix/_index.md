---
title: SVGTransform.Matrix
second_title: Referencia de API de Aspose.SVG para .NET
description: SVGTransform propiedad. La matriz que representa esta transformación. El objeto de matriz está activo lo que significa que cualquier cambio realizado en el objeto SVGTransform se refleja inmediatamente en el objeto de matriz y viceversa. En caso de que el objeto de matriz se cambie directamente es decir sin usar los métodos en la interfaz de SVGTransform en sí el tipo de SVGTransform cambia a SVG_TRANSFORM_MATRIX. Para SVG_TRANSFORM_MATRIX la matriz contiene a b c d e f valores proporcionados por el usuario. Para SVG_TRANSFORM_TRANSLATE e y f representan los montos de traducción a 1 b 0 c 0 y d  1. Para SVG_TRANSFORM_SCALE a y d representan los montos de escala b 0  c 0 e 0 y f  0. Para SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY a b c y d representan la matriz que dará como resultado el sesgo dado e 0 y f  0. Para SVG_TRANSFORM_ROTATE  a b c d e y f juntas representan la matriz que dará como resultado la rotación dada. Cuando la rotación es alrededor del punto central 0 0 e y f serán cero.
type: docs
weight: 20
url: /es/net/aspose.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

La matriz que representa esta transformación. El objeto de matriz está activo, lo que significa que cualquier cambio realizado en el objeto SVGTransform se refleja inmediatamente en el objeto de matriz y viceversa. En caso de que el objeto de matriz se cambie directamente (es decir, sin usar los métodos en la interfaz de SVGTransform en sí), el tipo de SVGTransform cambia a SVG_TRANSFORM_MATRIX. Para SVG_TRANSFORM_MATRIX, la matriz contiene a, b, c, d, e, f valores proporcionados por el usuario. Para SVG_TRANSFORM_TRANSLATE, e y f representan los montos de traducción (a= 1, b= 0, c= 0 y d = 1). Para SVG_TRANSFORM_SCALE, a y d representan los montos de escala (b= 0 , c= 0, e= 0 y f = 0). Para SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY, a, b, c y d representan la matriz que dará como resultado el sesgo dado (e= 0 y f = 0). Para SVG_TRANSFORM_ROTATE , a, b, c, d, e y f juntas representan la matriz que dará como resultado la rotación dada. Cuando la rotación es alrededor del punto central (0, 0), e y f serán cero.

```csharp
public SVGMatrix Matrix { get; }
```

### El valor de la propiedad

La matriz que representa esta transformación.

### Ver también

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* espacio de nombres [Aspose.Svg.DataTypes](../../svgtransform/)
* asamblea [Aspose.SVG](../../../)


