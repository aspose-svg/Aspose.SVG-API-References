---
title: "SVGBuilderExtensions.Points"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions Points. Establece el atributo points para un elemento SVG usando una matriz de dobles."
type: docs
weight: 1910
url: /es/net/aspose.svg.builder/svgbuilderextensions/points/
---
## Points<TBuilder>(*this TBuilder, params double[]*) {#points}

Establece el atributo 'points' para un elemento SVG usando una matriz de valores double.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params double[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| points | Una matriz de dobles que representa los puntos (debe ser un número par). |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si se proporciona un número impar de puntos. |

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Points<TBuilder>(*this TBuilder, params PointF[]*) {#points_1}

Establece el atributo 'points' para un elemento SVG usando una matriz de objetos PointF.

```csharp
public static TBuilder Points<TBuilder>(this TBuilder builder, params PointF[] points)
    where TBuilder : ISVGElementBuilder, IPointsAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| points | Una matriz de objetos PointF que representan los puntos. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPointsAttributeSetter](../../ipointsattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
