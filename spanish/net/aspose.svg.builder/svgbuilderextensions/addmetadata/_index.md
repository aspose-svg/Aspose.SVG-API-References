---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddMetadata. Añade una configuración de elemento metadata al constructor. El elemento metadata se utiliza para agregar metadatos al contenido SVG."
type: docs
weight: 390
url: /es/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

Agrega una configuración del elemento 'metadata' al generador. El elemento 'metadata' se usa para añadir metadatos al contenido SVG.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| TElement | El tipo que representa el elemento 'metadata' en el modelo SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'metadata'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
