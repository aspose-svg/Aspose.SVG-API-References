---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método TypeAndValues de SVGFEColorMatrixElementBuilder. Establece los atributos type y values del elemento feColorMatrix especificando la operación de matriz de color y sus parámetros"
type: docs
weight: 30
url: /es/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Establece los atributos 'type' y 'values' del elemento feColorMatrix, especificando la operación de la matriz de colores y sus parámetros.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | ColorMatrixOperation | El valor enum ColorMatrixOperation que representa el tipo de operación de matriz de color. |
| valores | Double[] | Los parámetros para la operación de matriz de color. |

### Valor de retorno

La instancia actual del builder.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando los valores proporcionados no coinciden con los requisitos del tipo especificado. |
| NotSupportedException | Se lanza cuando se proporciona un tipo de operación de matriz no compatible. |

### Ver también

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
