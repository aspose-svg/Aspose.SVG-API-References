---
title: "SVGBuilderExtensions.GradientUnits"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions GradientUnits. Imposta l'attributo gradientUnits per un elemento gradiente"
type: docs
weight: 990
url: /it/net/aspose.svg.builder/svgbuilderextensions/gradientunits/
---
## SVGBuilderExtensions.GradientUnits<TBuilder> method

Imposta l'attributo 'gradientUnits' per un elemento gradiente.

```csharp
public static TBuilder GradientUnits<TBuilder>(this TBuilder builder, CoordinateUnits units)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il builder dell'elemento SVG a cui viene applicato l'attributo. |
| unità | Le unità di coordinate per il gradiente (userSpaceOnUse o objectBoundingBox). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [CoordinateUnits](../../coordinateunits/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
