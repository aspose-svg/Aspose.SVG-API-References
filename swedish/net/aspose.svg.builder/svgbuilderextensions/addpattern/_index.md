---
title: "SVGBuilderExtensions.AddPattern"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddPattern-metod. Lägger till en konfiguration för ett pattern‑element i byggaren."
type: docs
weight: 410
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

Lägger till en 'pattern'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'pattern'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

Lägger till ett 'pattern'-element till SVG-byggaren, som specificerar koordinatsystemet och enheterna för pattern-innehållet.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen som 'pattern'-elementet kommer att läggas till. |
| patternUnits | Anger koordinatsystemet för pattern. Valfri parameter. |
| patternContentUnits | Anger koordinatsystemet för innehållet inom pattern. Valfri parameter. |
| href | Referensen till ett annat mönster, om tillämpligt. Valfri parameter. |
| id | Den unika identifieraren för mönsterelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera mönsterelementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
