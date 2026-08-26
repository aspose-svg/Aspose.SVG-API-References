---
title: "SVGBuilderExtensions.AddFeConvolveMatrix"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddFeConvolveMatrix-Methode. Fügt dem Builder eine feConvolveMatrix-Elementkonfiguration hinzu. Dieses Element wendet einen Matrix‑Faltungseffekt an."
type: docs
weight: 170
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfeconvolvematrix/
---
## AddFeConvolveMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix_1}

Fügt dem Builder eine 'feConvolveMatrix'-Elementkonfiguration hinzu. Dieses Element wendet einen Matrix-Faltung-Filtereffekt an.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEConvolveMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'feConvolveMatrix'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeConvolveMatrix<TBuilder>(*this TBuilder, double[], double?, double?, int?, int?, EdgeMode?, bool?, OneOf&lt;int, (int, int)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix}

Fügt dem SVG-Builder ein 'feConvolveMatrix'-Element hinzu, das einen Matrix-Faltung-Filtereffekt anwendet.

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    double[] kernelMatrix = null, double? divisor = null, double? bias = null, int? targetX = null, 
    int? targetY = null, EdgeMode? edgeMode = default, bool? preserveAlpha = null, 
    OneOf<int, (int, int)> order = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEConvolveMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'feConvolveMatrix'-Element hinzugefügt wird. |
| kernelMatrix | Die Matrix der Werte für die Faltung. Optionaler Parameter. |
| divisor | Der Divisor für die Faltung. Optionaler Parameter. |
| bias | Der Bias, der zum Ergebnis der Faltung hinzugefügt wird. Optionaler Parameter. |
| targetX | Die x‑Koordinate des Zielpixels in der Kernel‑Matrix. Optionaler Parameter. |
| targetY | Die y‑Koordinate des Zielpixels in der Kernel‑Matrix. Optionaler Parameter. |
| edgeMode | Definiert, wie Randpixel bei der Faltung behandelt werden. Optionaler Parameter. |
| preserveAlpha | Gibt an, ob der Alphakanal erhalten bleiben soll. Optionaler Parameter. |
| order | Die Ordnung der Kernel‑Matrix. Kann ein int oder ein ValueTuple aus zwei ints sein. Optionaler Parameter. |
| in | Der Eingabewert für den Faltungseffekt. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFEConvolveMatrixElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* enum [EdgeMode](../../edgemode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
