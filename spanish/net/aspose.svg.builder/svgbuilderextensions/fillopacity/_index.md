---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método FillOpacity de SVGBuilderExtensions. Establece el atributo fill-opacity para un elemento SVG. El valor debe estar entre 0.0 totalmente transparente y 1.0 totalmente opaco"
type: docs
weight: 820
url: /es/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Establece el atributo 'fill-opacity' para un elemento SVG. El valor debe estar entre 0.0 (totalmente transparente) y 1.0 (totalmente opaco).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| opacity | El valor de opacidad a establecer. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | Lanzada si la opacidad no está dentro del rango válido. |

### Ver también

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
