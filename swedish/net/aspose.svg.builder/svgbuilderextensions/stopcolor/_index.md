---
title: "SVGBuilderExtensions.StopColor"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions StopColor-metoden. Ställer in stop-color-attributet för ett SVG-element som definierar färgen vid ett gradientstopp"
type: docs
weight: 2060
url: /sv/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

Ställer in attributet 'stop-color' för ett SVG-element, vilket definierar färgen vid ett gradientstopp.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
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

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Ställer in attributet 'stop-color' för ett SVG-element med en anpassad färgkonfiguration.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
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
