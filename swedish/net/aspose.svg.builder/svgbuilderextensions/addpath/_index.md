---
title: "SVGBuilderExtensions.AddPath"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddPath metod. Lägger till en konfiguration för ett path‑element till byggaren"
type: docs
weight: 400
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

Lägger till en 'path'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'path'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

Lägger till ett 'path'-element till SVG-byggaren, som specificerar dess banadata och stilar.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen till vilken 'path'-elementet kommer att läggas till. |
| d | En OneOf‑typ som antingen kan vara en sträng som representerar path‑data eller en åtgärd som konfigurerar en PathBuilder. |
| fill | Fyllningsfärgen eller målningsstilen för path‑elementet. Kan vara ett Color‑ eller Paint‑enum‑värde eller ett paint‑server‑ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för path‑elementet. Kan vara ett Color‑ eller Paint‑enum‑värde eller ett paint‑server‑ID. Valfri parameter. |
| id | Den unika identifieraren för path‑elementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera path‑elementets byggare. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

Överlagring av AddPath som tar en åtgärd för att konfigurera en PathBuilder direkt.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen till vilken 'path'-elementet kommer att läggas till. |
| d | En åtgärd som konfigurerar en PathBuilder för att definiera path‑data. |
| fill | Fyllningsfärgen eller målningsstilen för path‑elementet. Kan vara ett Color‑ eller Paint‑enum‑värde eller ett paint‑server‑ID. Valfri parameter. |
| stroke | Streckfärgen eller målningsstilen för path‑elementet. Kan vara ett Color‑ eller Paint‑enum‑värde eller ett paint‑server‑ID. Valfri parameter. |
| id | Den unika identifieraren för path‑elementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera path‑elementets byggare. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
