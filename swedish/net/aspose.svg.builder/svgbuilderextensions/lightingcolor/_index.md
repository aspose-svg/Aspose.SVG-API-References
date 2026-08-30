---
title: "SVGBuilderExtensions.LightingColor"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions LightingColor‑metod. Ställer in lighting-color‑attributet för ett SVG‑element med ett angivet färgvärde."
type: docs
weight: 1110
url: /sv/net/aspose.svg.builder/svgbuilderextensions/lightingcolor/
---
## LightingColor<TBuilder>(*this TBuilder, Color*) {#lightingcolor_1}

Ställer in attributet 'lighting-color' för ett SVG-element med ett specificerat färgvärde.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| colorValue | Färgvärdet som ska sättas för ljuseffekten. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LightingColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#lightingcolor}

Ställer in attributet 'lighting-color' för ett SVG-element med en anpassad färgkonfiguration.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, 
    Action<ColorBuilder> configure)
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
