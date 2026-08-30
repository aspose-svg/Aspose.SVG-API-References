---
title: "SVGBuilderExtensions.AddAnimateTransform"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddAnimateTransform de SVGBuilderExtensions. Añade una configuración de elemento animateTransform al builder"
type: docs
weight: 50
url: /es/net/aspose.svg.builder/svgbuilderextensions/addanimatetransform/
---
## SVGBuilderExtensions.AddAnimateTransform<TBuilder> method

Añade una configuración de elemento 'animateTransform' al builder.

```csharp
public static TBuilder AddAnimateTransform<TBuilder>(this TBuilder builder, 
    Action<SVGAnimateTransformElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'animateTransform'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGAnimateTransformElementBuilder](../../svganimatetransformelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationElementBuilder](../../ianimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
