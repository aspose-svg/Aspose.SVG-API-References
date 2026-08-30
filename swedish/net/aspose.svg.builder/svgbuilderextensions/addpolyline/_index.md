---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddPolyline-metod. Lägger till en konfiguration för polyline‑elementet i byggaren"
type: docs
weight: 430
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Lägger till en 'polyline'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'polyline'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Lägger till ett 'polyline'-element till SVG-byggaren, som specificerar dess hörn och stilar.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen som 'polyline'-elementet kommer att läggas till. |
| points | En array av double‑värden som representerar punkterna i polyline (växlande x- och y‑koordinater). |
| fill | Fyllnadsfärgen eller målningsstilen för polyline. Kan vara ett Color‑ eller Paint‑enum‑värde eller ett paint‑server‑ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för polyline. Kan vara ett Color‑ eller Paint‑enum‑värde eller ett paint‑server‑ID. Valfri parameter. |
| id | Det unika identifieraren för polyline‑elementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera polyline‑elementbyggaren. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
