---
title: "SVGBuilderExtensions.TextLength"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método TextLength de SVGBuilderExtensions. Establece la longitud exacta del contenido de texto"
type: docs
weight: 2220
url: /es/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Establece la longitud exacta del contenido de texto.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | La longitud del texto. |
| type | El tipo de unidad de longitud para el valor. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método establece el atributo 'textLength', especificando la longitud deseada del contenido de texto, potencialmente sobrescribiendo la longitud natural del texto.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
