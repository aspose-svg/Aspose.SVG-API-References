---
title: "SVGBuilderExtensions.Color"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Color-metoden. Ställer in color-attributet för ett SVG-element med en anpassad konfiguration"
type: docs
weight: 670
url: /sv/net/aspose.svg.builder/svgbuilderextensions/color/
---
## Color<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#color}

Ställer in attributet 'color' för ett SVG-element med en anpassad konfiguration.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | En delegat för att konfigurera color. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Color<TBuilder>(*this TBuilder, Color*) {#color_1}

Ställer in attributet 'color' för ett SVG-element med ett färgvärde.

```csharp
public static TBuilder Color<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| colorValue | Color-värdet att sätta. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
