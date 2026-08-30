---
title: "SVGBuilderExtensions.Transform"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions Transform. Establece el atributo transform para un elemento SVG"
type: docs
weight: 2260
url: /es/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

Establece el atributo 'transform' para un elemento SVG.

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | Una función para configurar la transformación SVG. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
