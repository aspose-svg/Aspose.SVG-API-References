---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddImage-metod. Lägger till en bild-elementkonfiguration till byggaren"
type: docs
weight: 330
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Lägger till en 'image'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'image'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

Lägger till ett 'image'-element i SVG-byggaren, vilket bäddar in en extern bild i SVG-dokumentet.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken 'image'-elementet kommer att läggas till. |
| href | URL:en eller referensen till den externa bilden. Valfri parameter. |
| x | X-koordinaten där bilden placeras. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten där bilden placeras. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på bilden. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på bilden. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| id | Den unika identifieraren för bildelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGImageElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
