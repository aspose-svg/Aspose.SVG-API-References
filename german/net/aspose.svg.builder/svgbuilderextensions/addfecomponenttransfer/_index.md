---
title: "SVGBuilderExtensions.AddFeComponentTransfer"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddFeComponentTransfer-Methode. Fügt dem Builder eine feComponentTransfer-Elementkonfiguration hinzu. Dieses Element führt eine komponentenweise Neuzuordnung von Daten für Farbkanäle durch."
type: docs
weight: 150
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfecomponenttransfer/
---
## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer}

Fügt dem Builder eine 'feComponentTransfer'-Elementkonfiguration hinzu. Dieses Element führt eine komponentenweise Neuzuordnung von Daten für Farbkanäle durch.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEComponentTransferElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'feComponentTransfer'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEFuncAElementBuilder&gt;, Action&lt;SVGFEFuncRElementBuilder&gt;, Action&lt;SVGFEFuncGElementBuilder&gt;, Action&lt;SVGFEFuncBElementBuilder&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer_1}

Fügt dem SVG-Builder ein 'feComponentTransfer'-Element hinzu, das eine komponentenweise Neuzuordnung von Daten für Farbkanäle ermöglicht.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEFuncAElementBuilder> a = null, Action<SVGFEFuncRElementBuilder> r = null, 
    Action<SVGFEFuncGElementBuilder> g = null, Action<SVGFEFuncBElementBuilder> b = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEComponentTransferElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'feComponentTransfer'-Element hinzugefügt wird. |
| a | Eine Aktion, um die 'feFuncA'-Komponente für den Alpha-Kanal zu konfigurieren. Optionaler Parameter. |
| r | Eine Aktion, um die 'feFuncR'-Komponente für den Rot-Kanal zu konfigurieren. Optionaler Parameter. |
| g | Eine Aktion, um die 'feFuncG'-Komponente für den Grün-Kanal zu konfigurieren. Optionaler Parameter. |
| b | Eine Aktion, um die 'feFuncB'-Komponente für den blauen Kanal zu konfigurieren. Optionaler Parameter. |
| in | Die Eingabe für den Komponenten-Transfer-Effekt. Kann ein String oder ein FilterInput sein. Optionaler Parameter. |
| result | Der Ergebnisbezeichner für dieses Filter-Primitive. Optionaler Parameter. |
| x | Die x-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Subbereichs des Filter-Primitives. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| stroke | Die Strichfarbe, das Paint oder die Paint-Server-ID für das Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Primitive-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFEComponentTransferElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [SVGFEFuncAElementBuilder](../../svgfefuncaelementbuilder/)
* class [SVGFEFuncRElementBuilder](../../svgfefuncrelementbuilder/)
* class [SVGFEFuncGElementBuilder](../../svgfefuncgelementbuilder/)
* class [SVGFEFuncBElementBuilder](../../svgfefuncbelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
