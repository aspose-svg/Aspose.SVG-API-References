---
title: "SVGBuilderExtensions.AddFeDiffuseLighting"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddFeDiffuseLighting-Methode. Fügt dem Builder eine Konfiguration für ein feDiffuseLighting-Element hinzu. Dieses Element erzeugt einen Lichteffekt auf einem Bild."
type: docs
weight: 180
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfediffuselighting/
---
## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting}

Fügt dem Builder eine 'feDiffuseLighting'-Elementkonfiguration hinzu. Dieses Element erzeugt einen Lichteffekt auf einem Bild.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDiffuseLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'feDiffuseLighting'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_1}

Fügt dem SVG-Builder ein 'feDiffuseLighting'-Element hinzu, das einen diffusen Lichteffekt mit einer angegebenen Lichtquelle erzeugt.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'feDiffuseLighting'-Element hinzugefügt wird. |
| lightSource | Eine Aktion, um die Lichtquelle für den diffusen Lichteffekt zu konfigurieren. |
| lightingColor | Die Farbe des Lichts. Optionaler Parameter. |
| surfaceScale | Der Oberflächen‑Skalierungsfaktor für den Lichteffekt. Optionaler Parameter. |
| diffuseConstant | Die Konstante, die zur Bestimmung des Lichteffekts verwendet wird. Optionaler Parameter. |
| in | Der Eingabewert für den diffusen Lichteffekt. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFEDiffuseLightingElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_2}

Fügt dem SVG-Builder ein 'feDiffuseLighting'-Element hinzu, das einen diffusen Lichteffekt mit einer angegebenen Lichtquelle erzeugt.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'feDiffuseLighting'-Element hinzugefügt wird. |
| lightSource | Eine Aktion, um die Lichtquelle für den diffusen Lichteffekt zu konfigurieren. |
| lightingColor | Die Farbe des Lichts. Optionaler Parameter. |
| surfaceScale | Der Oberflächen‑Skalierungsfaktor für den Lichteffekt. Optionaler Parameter. |
| diffuseConstant | Die Konstante, die zur Bestimmung des Lichteffekts verwendet wird. Optionaler Parameter. |
| in | Der Eingabewert für den diffusen Lichteffekt. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFEDiffuseLightingElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_3}

Fügt dem SVG-Builder ein 'feDiffuseLighting'-Element hinzu, das einen diffusen Lichteffekt mit einer angegebenen Lichtquelle erzeugt.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'feDiffuseLighting'-Element hinzugefügt wird. |
| lightSource | Eine Aktion, um die Lichtquelle für den diffusen Lichteffekt zu konfigurieren. |
| lightingColor | Die Farbe des Lichts. Optionaler Parameter. |
| surfaceScale | Der Oberflächen‑Skalierungsfaktor für den Lichteffekt. Optionaler Parameter. |
| diffuseConstant | Die Konstante, die zur Bestimmung des Lichteffekts verwendet wird. Optionaler Parameter. |
| in | Der Eingabewert für den diffusen Lichteffekt. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFEDiffuseLightingElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
