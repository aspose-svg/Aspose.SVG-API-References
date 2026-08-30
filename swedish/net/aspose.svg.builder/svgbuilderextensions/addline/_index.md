---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddLine-metoden. Lägger till en linje‑elementkonfiguration till byggaren"
type: docs
weight: 350
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Lägger till en 'line'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'line'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Lägger till ett 'line'-element med angivna start- och slutpunkter samt stilar till SVG-byggaren.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen till vilken 'line'-elementet kommer att läggas till. |
| x1 | X‑koordinaten för linjens startpunkt. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| y1 | Y‑koordinaten för linjens startpunkt. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| x2 | X‑koordinaten för linjens slutpunkt. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| y2 | Y-koordinaten för linjens slutpunkt. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| fill | Fyllningsfärgen eller målningsstilen för linjen. Kan vara en Color eller ett Paint‑enum‑värde eller paint‑server‑ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för linjen. Kan vara en Color eller ett Paint‑enum‑värde eller paint‑server‑ID. Valfri parameter. |
| id | Det unika identifieraren för linjeelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera linjeelement‑byggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
