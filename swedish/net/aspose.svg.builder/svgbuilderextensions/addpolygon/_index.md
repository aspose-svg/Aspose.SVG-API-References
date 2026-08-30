---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddPolygon-metod. Lägger till en polygon-elementkonfiguration till byggaren"
type: docs
weight: 420
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Lägger till en 'polygon'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'polygon'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Lägger till ett 'polygon'-element till SVG-byggaren, som specificerar dess hörn och stilar.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken 'polygon'-elementet kommer att läggas till. |
| points | En array av dubbla värden som representerar polygonens punkter (alternerande x- och y-koordinater). |
| fill | Fyllningsfärgen eller målningsstilen för polygonen. Kan vara ett Color- eller Paint-enumvärde eller paint-server-ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för polygonen. Kan vara ett Color- och Paint-enumvärde eller paint-server-ID. Valfri parameter. |
| id | Det unika identifieraren för polygon-elementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera polygon-elementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
