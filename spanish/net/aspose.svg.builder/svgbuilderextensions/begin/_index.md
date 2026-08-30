---
title: "SVGBuilderExtensions.Begin"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Begin de SVGBuilderExtensions. Establece el atributo begin que define cuándo debe iniciar la animación"
type: docs
weight: 610
url: /es/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Establece el atributo 'begin', definiendo cuándo debe iniciar la animación.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| configurar | Un delegado para configurar el valor de tiempo. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
