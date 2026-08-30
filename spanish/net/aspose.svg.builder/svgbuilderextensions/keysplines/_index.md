---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método KeySplines de SVGBuilderExtensions. Establece el atributo keySplines que especifica los puntos de control para el ritmo de la animación."
type: docs
weight: 1060
url: /es/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Establece el atributo 'keySplines', especificando los puntos de control para el ritmo de la animación.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| buildSplines | La acción para construir la configuración de la spline. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
