---
title: "SVGBuilderExtensions.AddFeSpecularLighting"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddFeSpecularLighting Methode. Fügt dem Builder eine feSpecularLighting‑Element‑Konfiguration hinzu. Dieses Element wendet einen Lichteffekt auf das Bild an, der eine spekulare Reflexion simuliert."
type: docs
weight: 270
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfespecularlighting/
---
## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_2}

Fügt dem Builder eine 'feSpecularLighting'-Elementkonfiguration hinzu. Dieses Element wendet einen Lichteffekt auf das Bild an und simuliert spekulare Reflexion.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpecularLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'feSpecularLighting'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting}

Fügt dem SVG-Builder ein 'feSpecularLighting'-Element hinzu, das einen spekularen Lichteffekt mit einer angegebenen Lichtquelle anwendet.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'feSpecularLighting'-Element hinzugefügt wird. |
| lightSource | Eine Aktion, um die Lichtquelle für den spekularen Lichteffekt zu konfigurieren. |
| lightingColor | Die Farbe des Lichts. Optionaler Parameter. |
| surfaceScale | Der Oberflächen‑Skalierungsfaktor für den Lichteffekt. Optionaler Parameter. |
| specularConstant | Die Konstante, die zur Skalierung des spekularen Terms verwendet wird. Optionaler Parameter. |
| specularExponent | Der Exponent für den spekularen Term, der den Fokus des spekularen Highlights steuert. Optionaler Parameter. |
| kernelUnitLength | Die Kernel-Einheitslänge für den Faltungfilter. Kann ein double oder ein ValueTuple aus zwei doubles sein. Optionaler Parameter. |
| in | Das Eingabebild, auf das der spekulare Lichteffekt angewendet wird. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFESpecularLightingElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_1}

Fügt dem SVG-Builder ein 'feSpecularLighting'-Element hinzu, das einen spekularen Lichteffekt mit einer angegebenen Lichtquelle anwendet.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'feSpecularLighting'-Element hinzugefügt wird. |
| lightSource | Eine Aktion, um die Lichtquelle für den spekularen Lichteffekt zu konfigurieren. |
| lightingColor | Die Farbe des Lichts. Optionaler Parameter. |
| surfaceScale | Der Oberflächen‑Skalierungsfaktor für den Lichteffekt. Optionaler Parameter. |
| specularConstant | Die Konstante, die zur Skalierung des spekularen Terms verwendet wird. Optionaler Parameter. |
| specularExponent | Der Exponent für den spekularen Term, der den Fokus des spekularen Highlights steuert. Optionaler Parameter. |
| kernelUnitLength | Die Kernel-Einheitslänge für den Faltungfilter. Kann ein double oder ein ValueTuple aus zwei doubles sein. Optionaler Parameter. |
| in | Das Eingabebild, auf das der spekulare Lichteffekt angewendet wird. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFESpecularLightingElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_3}

Fügt dem SVG-Builder ein 'feSpecularLighting'-Element hinzu, das einen spekularen Lichteffekt mit einer angegebenen Lichtquelle anwendet.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'feSpecularLighting'-Element hinzugefügt wird. |
| lightSource | Eine Aktion, um die Lichtquelle für den spekularen Lichteffekt zu konfigurieren. |
| lightingColor | Die Farbe des Lichts. Optionaler Parameter. |
| surfaceScale | Der Oberflächen‑Skalierungsfaktor für den Lichteffekt. Optionaler Parameter. |
| specularConstant | Die Konstante, die zur Skalierung des spekularen Terms verwendet wird. Optionaler Parameter. |
| specularExponent | Der Exponent für den spekularen Term, der den Fokus des spekularen Highlights steuert. Optionaler Parameter. |
| kernelUnitLength | Die Kernel-Einheitslänge für den Faltungfilter. Kann ein double oder ein ValueTuple aus zwei doubles sein. Optionaler Parameter. |
| in | Das Eingabebild, auf das der spekulare Lichteffekt angewendet wird. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFESpecularLightingElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
