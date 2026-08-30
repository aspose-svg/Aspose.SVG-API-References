---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddDesc de SVGBuilderExtensions. Añade una configuración del elemento desc al constructor. El elemento desc se utiliza para proporcionar una descripción del contenido SVG"
type: docs
weight: 110
url: /es/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

Agrega una configuración de elemento 'desc' al creador. El elemento 'desc' se utiliza para proporcionar una descripción del contenido SVG.

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'desc'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
