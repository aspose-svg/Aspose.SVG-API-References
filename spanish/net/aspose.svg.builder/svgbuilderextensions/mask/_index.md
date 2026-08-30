---
title: "SVGBuilderExtensions.Mask"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Mask de SVGBuilderExtensions. Establece el atributo mask para un elemento SVG usando una configuración de máscara personalizada"
type: docs
weight: 1150
url: /es/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Establece el atributo 'mask' para un elemento SVG usando una configuración de máscara personalizada.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | Un delegado para configurar la máscara. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
