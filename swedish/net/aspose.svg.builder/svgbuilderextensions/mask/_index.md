---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Mask metod. Ställer in mask-attributet för ett SVG-element med en anpassad maskkonfiguration"
type: docs
weight: 1150
url: /sv/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Ställer in attributet 'mask' för ett SVG-element med en anpassad maskkonfiguration.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | En delegat för att konfigurera masken. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
