---
title: "SVGBuilderExtensions.AddFeGaussianBlur"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Methode SVGBuilderExtensions AddFeGaussianBlur. Fügt dem Builder eine feGaussianBlur-Elementkonfiguration hinzu. Dieses Element wendet einen Gaußschen Weichzeichner auf das Eingabebild an."
type: docs
weight: 220
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfegaussianblur/
---
## AddFeGaussianBlur<TBuilder>(*this TBuilder, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur_1}

Fügt dem Builder eine 'feGaussianBlur'-Elementkonfiguration hinzu. Dieses Element wendet eine Gaußsche Unschärfe auf das Eingabebild an.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    Action<SVGFEGaussianBlurElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das Element 'feGaussianBlur'. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeGaussianBlur<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur}

Fügt dem SVG-Builder ein 'feGaussianBlur'-Element hinzu, das einen Gaußschen Unschärfeeffekt auf das Eingabebild anwendet.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> stdDeviation = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEGaussianBlurElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das Element 'feGaussianBlur' hinzugefügt wird. |
| stdDeviation | Die Standardabweichung für den Weichzeichnungsvorgang. Kann ein double oder ein ValueTuple aus zwei doubles sein. Optionaler Parameter. |
| in | Das Eingabebild, auf das der Gaußsche Weichzeichner angewendet wird. Kann ein string oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFEGaussianBlurElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
