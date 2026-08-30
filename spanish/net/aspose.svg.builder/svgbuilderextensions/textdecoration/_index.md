---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método TextDecoration de SVGBuilderExtensions. Establece el atributo text-decoration para un elemento SVG que define las decoraciones que se añaden al texto"
type: docs
weight: 2210
url: /es/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Establece el atributo 'text-decoration' para un elemento SVG, definiendo las decoraciones que se añaden al texto.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| subrayado | Especifica si el texto debe estar subrayado. |
| sobrerayado | Especifica si el texto debe tener una línea superior. |
| tachado | Especifica si el texto debe estar tachado. |
| parpadeo | Especifica si el texto debe parpadear (no se recomienda su uso). |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
