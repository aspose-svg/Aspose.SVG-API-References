---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Filter-metod. Ställer in filter-attributet för ett SVG-element med en anpassad konfiguration."
type: docs
weight: 840
url: /sv/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Ställer in attributet 'filter' för ett SVG-element med en anpassad konfiguration.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | En delegat för att konfigurera FilterValueListBuilder. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
