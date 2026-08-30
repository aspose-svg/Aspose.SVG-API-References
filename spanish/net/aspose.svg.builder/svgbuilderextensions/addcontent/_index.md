---
title: "SVGBuilderExtensions.AddContent"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddContent de SVGBuilderExtensions. Añade contenido de texto al elemento SVG."
type: docs
weight: 90
url: /es/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Agrega contenido de texto al elemento SVG.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| texto | El texto que se añadirá al elemento. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método permite añadir contenido de texto directamente a un elemento SVG. Es útil para elementos que contienen datos textuales.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
