---
title: "SVGBuilderExtensions.AddClipPath"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddClipPath de SVGBuilderExtensions. Añade una configuración de elemento clipPath al constructor"
type: docs
weight: 80
url: /es/net/aspose.svg.builder/svgbuilderextensions/addclippath/
---
## SVGBuilderExtensions.AddClipPath<TBuilder> method

Agrega una configuración de elemento 'clipPath' al creador.

```csharp
public static TBuilder AddClipPath<TBuilder>(this TBuilder builder, 
    Action<SVGClipPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'clipPath'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGClipPathElementBuilder](../../svgclippathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
