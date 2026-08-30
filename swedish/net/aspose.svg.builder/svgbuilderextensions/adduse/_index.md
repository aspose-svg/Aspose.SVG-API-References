---
title: "SVGBuilderExtensions.AddUse"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddUse-metoden. Lägger till en use‑elementkonfiguration till byggaren."
type: docs
weight: 550
url: /sv/net/aspose.svg.builder/svgbuilderextensions/adduse/
---
## AddUse<TBuilder>(*this TBuilder, Action&lt;SVGUseElementBuilder&gt;*) {#adduse}

Lägger till en 'use' elementkonfiguration till byggaren.

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, 
    Action<SVGUseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'use'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddUse<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGUseElementBuilder&gt;*) {#adduse_1}

Lägger till ett 'use'-element till SVG-byggaren, vilket möjliggör återanvändning av ett befintligt element som definierats någon annanstans i SVG.

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGUseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen som 'use'-elementet kommer att läggas till. |
| href | Referensen till det befintliga elementet som ska återanvändas. Valfri parameter. |
| x | X‑koordinaten där det återanvända elementet placeras. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| y | Y‑koordinaten där det återanvända elementet placeras. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på det återanvända elementet. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på det återanvända elementet. Kan vara en double eller ett ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Det unika identifieraren för elementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGUseElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
