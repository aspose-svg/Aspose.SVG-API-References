---
title: "SVGBuilderExtensions.AddMask"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddMask de SVGBuilderExtensions. Añade una configuración de elemento mask al builder"
type: docs
weight: 380
url: /es/net/aspose.svg.builder/svgbuilderextensions/addmask/
---
## SVGBuilderExtensions.AddMask<TBuilder> method

Agrega una configuración del elemento 'mask' al generador.

```csharp
public static TBuilder AddMask<TBuilder>(this TBuilder builder, 
    Action<SVGMaskElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'mask'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGMaskElementBuilder](../../svgmaskelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
