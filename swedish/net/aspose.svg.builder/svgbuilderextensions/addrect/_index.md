---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddRect-metod. Lägger till en rect-elementkonfiguration till byggaren"
type: docs
weight: 450
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Lägger till en 'rect'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'rect'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Lägger till ett 'rect' (rektangel)-element med angivna dimensioner och stilar till SVG-byggaren.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken 'rect'-elementet kommer att läggas till. |
| x | X-koordinaten för rektangelns startpunkt. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| y | Y-koordinaten för rektangelns startpunkt. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| width | Bredden på rektangeln. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| height | Höjden på rektangeln. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| fill | Fyllningsfärgen eller målningsstilen för rektangeln. Kan vara en Color eller ett Paint-enumvärde eller paint server-ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för rektangelns kontur. Kan vara en Color eller ett Paint-enumvärde eller paint server-ID. Valfri parameter. |
| id | Det unika identifieraren för rektangel-elementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera rektangel-elementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
