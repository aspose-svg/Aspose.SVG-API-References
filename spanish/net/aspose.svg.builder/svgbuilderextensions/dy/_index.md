---
title: "SVGBuilderExtensions.Dy"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Dy de SVGBuilderExtensions. Establece múltiples valores de ajuste vertical para el contenido de texto."
type: docs
weight: 780
url: /es/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

Establece varios valores de ajuste vertical para el contenido de texto.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| valores | La matriz de valores de ajuste vertical. |
| type | El tipo de unidad de longitud para los valores. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método establece el atributo 'dy' con múltiples valores, permitiendo ajustes verticales individuales para cada carácter o segmento de texto.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

Establece un único valor de ajuste vertical para el contenido de texto.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | El valor de ajuste vertical. |
| type | El tipo de unidad de longitud para el valor. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método establece el atributo 'dy' con un solo valor, ajustando la posición vertical del contenido de texto.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
