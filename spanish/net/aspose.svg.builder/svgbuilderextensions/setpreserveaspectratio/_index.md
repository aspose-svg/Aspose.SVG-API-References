---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions SetPreserveAspectRatio. Establece el atributo preserveAspectRatio para un elemento SVG."
type: docs
weight: 2020
url: /es/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Establece el atributo 'preserveAspectRatio' para un elemento SVG.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| align | La configuración de alineación para la relación de aspecto. |
| meetOrSlice | Especifica cómo se conserva una relación de aspecto (el valor predeterminado es 'Meet'). |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
