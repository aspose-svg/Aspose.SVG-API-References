---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions RequiredExtensions-metoden. Ställer in requiredExtensions-attributet på SVG-elementet. Detta attribut specificerar vilka tillägg som krävs för att SVG-dokumentfragmentet ska bearbetas."
type: docs
weight: 1970
url: /sv/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

Ställer in 'requiredExtensions'-attributet på SVG-elementet. Detta attribut specificerar vilka tillägg som krävs för att SVG-dokumentfragmentet ska kunna bearbetas.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren på vilken attributet sätts. |
| value | Ett strängvärde som representerar de erforderliga tilläggen. |

### Returvärde

Den ursprungliga SVG-elementbyggaren för metodkedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
