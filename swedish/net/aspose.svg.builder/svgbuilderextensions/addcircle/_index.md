---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddCircle‑metoden. Lägger till en cirkelelementkonfiguration i byggaren."
type: docs
weight: 70
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Lägger till en 'circle'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'circle'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Lägger till ett 'circle'-element med angivet centrum, radie och stilar till SVG-byggaren.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen som 'circle'-elementet kommer att läggas till. |
| cx | X‑koordinaten för cirkelns centrum. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| cy | Y‑koordinaten för cirkelns centrum. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| r | Radien för cirkeln. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| fill | Fyllnadsfärgen eller målningsstilen för cirkeln. Kan vara en Color eller ett Paint‑enum‑värde eller paint‑server‑ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för cirkelns kontur. Kan vara en Color eller ett Paint‑enum‑värde eller paint‑server‑ID. Valfri parameter. |
| id | Det unika identifieraren för cirkelelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera cirkelelementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
