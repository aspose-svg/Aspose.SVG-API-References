---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddLinearGradient-metoden. Lägger till en linearGradient-elementkonfiguration till byggaren."
type: docs
weight: 360
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Lägger till en 'linearGradient'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'linearGradient'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Lägger till ett 'linearGradient'-element till SVG-byggaren, som specificerar dess start- och slutpositioner samt andra gradientegenskaper.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen som 'linearGradient'-elementet kommer att läggas till. |
| x1 | Start-x-koordinaten för gradienten. Kan vara en double eller ett ValueTuple med LengthType. |
| y1 | Start-y-koordinaten för gradienten. Kan vara en double eller ett ValueTuple med LengthType. |
| x2 | Slut-x-koordinaten för gradienten. Kan vara en double eller ett ValueTuple med LengthType. |
| y2 | Slut-y-koordinaten för gradienten. Kan vara en double eller ett ValueTuple med LengthType. |
| gradientUnits | Anger koordinatsystemet för gradienten. Valfri parameter. |
| spreadMethod | Definierar hur gradienten sprider sig bortom sina start- och slutpunkter. Valfri parameter. |
| href | Referensen till en annan gradient, om tillämpligt. Valfri parameter. |
| id | Den unika identifieraren för gradientelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera den linjära gradient‑elementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
