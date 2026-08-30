---
title: "SVGBuilderExtensions.By"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método By de SVGBuilderExtensions. Establece el atributo by que define el valor de desplazamiento relativo para la animación con un tipo de longitud especificado"
type: docs
weight: 620
url: /es/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Establece el atributo 'by', definiendo el valor de desplazamiento relativo para la animación con un tipo de longitud especificado.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | El valor de desplazamiento relativo para la animación. |
| type | El tipo de longitud para el valor 'by'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
