---
title: "SVGBuilderExtensions.Filter"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Filter de SVGBuilderExtensions. Establece el atributo filter para un elemento SVG usando una configuración personalizada"
type: docs
weight: 840
url: /es/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Establece el atributo 'filter' para un elemento SVG usando una configuración personalizada.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | Un delegado para configurar el FilterValueListBuilder. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
