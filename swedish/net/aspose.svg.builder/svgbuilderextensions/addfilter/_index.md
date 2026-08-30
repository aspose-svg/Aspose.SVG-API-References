---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFilter-metoden. Lägger till en filterelementkonfiguration i byggaren"
type: docs
weight: 300
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Lägger till en 'filter'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'filter'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Lägger till ett 'filter'-element i SVG-byggaren, vilket definierar en filtereffekt som kan tillämpas på SVG-element.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen som 'filter'-elementet kommer att läggas till. |
| filterUnits | Anger koordinatsystemet för filterets x-, y-, bredd- och höjdattribut. Valfri parameter. |
| primitiveUnits | Anger koordinatsystemet för attributen hos filterets underordnade element. Valfri parameter. |
| x | X‑koordinaten för filterregionen. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| y | Y‑koordinaten för filterregionen. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterregionen. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterregionen. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen eller målning för filterelementet. Valfri parameter. |
| stroke | Streckfärgen eller målning för filterelementet. Valfri parameter. |
| id | Den unika identifieraren för filterelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFilterElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
