---
title: "SVGBuilderExtensions.From"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método From de SVGBuilderExtensions. Establece el atributo from que define el valor inicial de la animación con un tipo de longitud especificado"
type: docs
weight: 960
url: /es/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Establece el atributo 'from', definiendo el valor inicial de la animación con un tipo de longitud especificado.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | El valor inicial de la animación. |
| type | El tipo de longitud para el valor 'from'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
