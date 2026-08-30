---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddRadialGradient‑metod. Lägger till en radialGradient‑elementkonfiguration till byggaren."
type: docs
weight: 440
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Lägger till en 'radialGradient'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för elementet 'radialGradient'. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Lägger till ett 'radialGradient'-element till SVG-byggaren, som specificerar dess centrum, radie och fokuspunkter samt andra gradientegenskaper.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken elementet 'radialGradient' kommer att läggas till. |
| cx | X-koordinaten för gradientens centrum. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| cy | Y-koordinaten för gradientens centrum. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| r | Radien för gradienten. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fx | X-koordinaten för gradientens fokalpunkt. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fy | Y-koordinaten för gradientens fokalpunkt. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| gradientUnits | Anger koordinatsystemet för gradienten. Valfri parameter. |
| spreadMethod | Definierar hur gradienten sprider sig bortom sina start- och slutpunkter. Valfri parameter. |
| href | Referensen till en annan gradient, om tillämpligt. Valfri parameter. |
| id | Den unika identifieraren för gradientelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera den radiella gradientelementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
