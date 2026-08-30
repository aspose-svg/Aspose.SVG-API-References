---
title: "SVGBuilderExtensions.Min"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions Min-metoden. Ställer in min‑attributet som specificerar den minsta varaktigheten för animationen"
type: docs
weight: 1170
url: /sv/net/aspose.svg.builder/svgbuilderextensions/min/
---
## Min<TBuilder>(*this TBuilder, TimeSpan*) {#min_1}

Ställer in attributet 'min' och anger den minsta varaktigheten för animationen.

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| varaktighet | Den minsta varaktigheten för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Min<TBuilder>(*this TBuilder, [Media](../../media/)*) {#min}

Ställer in attributet 'min' och anger det minsta varaktighetsvillkoret för animationen baserat på media.

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | Det mediarelaterade minsta varaktighetsvillkoret för animationen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
