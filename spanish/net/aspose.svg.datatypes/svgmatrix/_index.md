---
title: Class SVGMatrix
second_title: Referencia de API de Aspose.SVG para .NET
description: Aspose.Svg.DataTypes.SVGMatrix clase. Muchas de las operaciones gráficas de SVG utilizan matrices de 2x3 de la forma ace bdf que cuando se expanden a una matriz de 3x3 para propósitos de aritmética de matrices se convierten en ace bdf 0 0 1
type: docs
weight: 240
url: /es/net/aspose.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Muchas de las operaciones gráficas de SVG utilizan matrices de 2x3 de la forma: [ace] [bdf] que, cuando se expanden a una matriz de 3x3 para propósitos de aritmética de matrices, se convierten en: [ace] [bdf] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [A](../../aspose.svg.datatypes/svgmatrix/a/) { get; set; } | La componente A de la matriz. |
| [B](../../aspose.svg.datatypes/svgmatrix/b/) { get; set; } | La componente B de la matriz. |
| [C](../../aspose.svg.datatypes/svgmatrix/c/) { get; set; } | La componente C de la matriz. |
| [D](../../aspose.svg.datatypes/svgmatrix/d/) { get; set; } | La componente D de la matriz. |
| [E](../../aspose.svg.datatypes/svgmatrix/e/) { get; set; } | La componente E de la matriz. |
| [F](../../aspose.svg.datatypes/svgmatrix/f/) { get; set; } | La componente F de la matriz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [Multiply](../../aspose.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Realiza la multiplicación de matrices. Esta matriz se multiplica posteriormente por otra matriz, devolviendo la nueva matriz resultante. |
| [Rotate](../../aspose.svg.datatypes/svgmatrix/rotate/)(float) | Post-multiplica una transformación de rotación en la matriz actual y devuelve la matriz resultante. |
| [Scale](../../aspose.svg.datatypes/svgmatrix/scale/)(float) | Post-multiplica una transformación de escala uniforme en la matriz actual y devuelve la matriz resultante. |
| [ScaleNonUniform](../../aspose.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multiplica una transformación de escala no uniforme en la matriz actual y devuelve la matriz resultante. |
| [SkewX](../../aspose.svg.datatypes/svgmatrix/skewx/)(float) | Post-multiplica una transformación skewX en la matriz actual y devuelve la matriz resultante. |
| [SkewY](../../aspose.svg.datatypes/svgmatrix/skewy/)(float) | Post-multiplica una transformación sesgada en la matriz actual y devuelve la matriz resultante. |
| override [ToString](../../aspose.svg.datatypes/svgmatrix/tostring/)() | Devuelve unString que representa esta instancia. |
| [Translate](../../aspose.svg.datatypes/svgmatrix/translate/)(float, float) | Post-multiplica una transformación de traducción en la matriz actual y devuelve la matriz resultante. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* espacio de nombres [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* asamblea [Aspose.SVG](../../)


