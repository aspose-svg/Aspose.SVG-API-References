---
title: "SVGBuilderExtensions.End"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método End de SVGBuilderExtensions. Establece el atributo end que define cuándo debe terminar la animación."
type: docs
weight: 790
url: /es/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

Establece el atributo 'end', definiendo cuándo debe terminar la animación.

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
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
