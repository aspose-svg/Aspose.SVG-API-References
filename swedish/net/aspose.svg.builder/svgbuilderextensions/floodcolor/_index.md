---
title: "SVGBuilderExtensions.FloodColor"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions FloodColor-metoden. Ställer in flood-color-attributet för ett SVG-element med en System.Drawing-färg."
type: docs
weight: 850
url: /sv/net/aspose.svg.builder/svgbuilderextensions/floodcolor/
---
## FloodColor<TBuilder>(*this TBuilder, Color*) {#floodcolor_1}

Ställer in attributet 'flood-color' för ett SVG-element med en System.Drawing‑färg.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| colorValue | Färgen som ska sättas som översvämningsfärg. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FloodColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#floodcolor}

Ställer in attributet 'flood-color' för ett SVG-element med en anpassad färgkonfiguration.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | En delegat för att konfigurera ColorBuilder. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
