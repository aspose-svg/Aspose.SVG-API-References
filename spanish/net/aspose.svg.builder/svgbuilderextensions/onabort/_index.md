---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método OnAbort de SVGBuilderExtensions. Establece el atributo de evento onabort que define un script a ejecutar cuando se aborta la carga de un documento SVG."
type: docs
weight: 1190
url: /es/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

Establece el atributo de evento 'onabort', definiendo un script que se ejecuta cuando se aborta la carga de un documento SVG.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | La función o script JavaScript a ejecutar cuando se aborta la carga del documento. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
