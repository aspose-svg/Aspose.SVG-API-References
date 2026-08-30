---
title: "SVGBuilderExtensions.To"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método To de SVGBuilderExtensions. Establece el atributo to que define el valor final de la animación con un tipo de longitud especificado"
type: docs
weight: 2250
url: /es/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Establece el atributo 'to', definiendo el valor final de la animación con un tipo de longitud especificado.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | El valor final de la animación. |
| type | El tipo de longitud para el valor 'to'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
