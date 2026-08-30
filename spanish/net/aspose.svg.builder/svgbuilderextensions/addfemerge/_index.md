---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddFeMerge. Añade una configuración de elemento feMerge al constructor. Este elemento permite que los efectos de filtro se apliquen de forma concurrente en lugar de secuencial."
type: docs
weight: 240
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Agrega una configuración del elemento 'feMerge' al constructor. Este elemento permite que los efectos de filtro se apliquen de forma concurrente en lugar de secuencialmente.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'feMerge'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
