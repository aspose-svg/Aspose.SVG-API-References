---
title: "SVGBuilderExtensions.Rect"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions Rect. Establece los atributos x, y, width y height para un elemento SVG para definir un rectángulo"
type: docs
weight: 1920
url: /es/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Establece los atributos 'x', 'y', 'width' y 'height' para un elemento SVG para definir un rectángulo.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| x | La coordenada x del rectángulo. |
| y | La coordenada y del rectángulo. |
| width | El ancho del rectángulo. |
| altura | La altura del rectángulo. |
| type | El tipo de medida de longitud para todas las dimensiones (el valor predeterminado es píxeles). |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
