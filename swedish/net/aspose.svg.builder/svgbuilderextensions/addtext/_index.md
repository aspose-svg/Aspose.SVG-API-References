---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddText-metod. Lägger till en textelementkonfiguration i byggaren"
type: docs
weight: 530
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Lägger till en 'text' elementkonfiguration till byggaren.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'text'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Lägger till ett 'text'-element med specificerat innehåll och attribut till SVG-byggaren.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren, vilket möjliggör kedjning. |
| byggare | Byggarinstansen som 'text'-elementet kommer att läggas till. |
| innehåll | Textinnehållet som ska visas inom 'text'-elementet. |
| x | X-koordinaten för textelementet. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| y | Y-koordinaten för textelementet. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| fontSize | Teckenstorleken för texten. Kan vara ett dubbelvärde eller en tupel av dubbel och LengthType. |
| fontStyle | Teckensnittsstilen för texten (t.ex. normal, kursiv, sned). |
| fontFamily | Teckensnittsfamiljen för texten (t.ex. Arial, Verdana). |
| fontWeight | Vikten (tjockleken) på teckensnittet (t.ex. normal, fet). |
| fill | Fyllningsfärgen eller målningsstilen för texten. Kan vara en Color eller ett Paint‑enum‑värde eller paint‑server‑ID. |
| stroke | Streckfärgen eller målningsstilen för texten. Kan vara en Color eller ett Paint‑enum‑värde eller paint‑server‑ID. |
| id | Den unika identifieraren för textelementet. |
| extend | En valfri åtgärd för att ytterligare konfigurera textelement‑byggaren. |

### Returvärde

Byggarinstansen för att kedja ytterligare tillägg eller konfigurationer.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
