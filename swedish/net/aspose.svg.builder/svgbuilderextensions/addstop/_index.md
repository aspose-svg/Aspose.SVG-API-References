---
title: "SVGBuilderExtensions.AddStop"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddStop‑metod. Lägger till en stop‑elementkonfiguration i byggaren för att definiera gradientstopp"
type: docs
weight: 480
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

Lägger till en 'stop'-elementkonfiguration till byggaren för att definiera gradientstopp.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'stop'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

Lägger till ett 'stop'-element till gradienten i SVG-byggaren, som specificerar färg och opacitet vid ett specifikt offset.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken 'stop'-elementet kommer att läggas till. |
| stopColor | Färgen vid stoppet. Valfri parameter. |
| stopOpacity | Opaciteten vid stoppet. Valfri parameter. |
| offset | Förskjutningen för stoppet inom gradienten. Kan vara en double eller ett ValueTuple med StopUnitType. Valfri parameter. |
| id | Den unika identifieraren för stoppelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera stoppelementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
