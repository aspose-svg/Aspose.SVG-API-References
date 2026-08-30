---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddEllipse-metoden. Lägger till en ellips‑elementkonfiguration i byggaren."
type: docs
weight: 120
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Lägger till en 'ellipse'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'ellipse'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Lägger till ett 'ellipse'-element till SVG-byggaren, med angivet centrum, radier och stilar.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen som 'ellipse'-elementet kommer att läggas till. |
| cx | X‑koordinaten för ellipsens centrum. Kan vara ett double‑värde eller en tupel av double och LengthType. |
| cy | Y‑koordinaten för ellipsens centrum. Kan vara ett double‑värde eller en tupel av double och LengthType. |
| rx | x-radius för ellipsen. Kan vara ett double‑värde eller en tupel av double och LengthType. |
| ry | y-radius för ellipsen. Kan vara ett double‑värde eller en tupel av double och LengthType. |
| fill | Fyllningsfärgen eller målningsstilen för ellipsen. Kan vara ett Color‑värde eller ett Paint‑enum‑värde eller paint‑server‑ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för ellipsen. Kan vara ett Color‑värde eller ett Paint‑enum‑värde eller paint‑server‑ID. Valfri parameter. |
| id | Det unika identifieraren för ellipselementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera ellips‑element‑byggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
