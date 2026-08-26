---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddFilter-Methode. Fügt dem Builder eine Filter-Element-Konfiguration hinzu"
type: docs
weight: 300
url: /de/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Fügt dem Builder eine 'filter'-Elementkonfiguration hinzu.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'filter'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Fügt dem SVG-Builder ein 'filter'-Element hinzu, das einen Filtereffekt definiert, der auf SVG-Elemente angewendet werden kann.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'filter'-Element hinzugefügt wird. |
| filterUnits | Gibt das Koordinatensystem für die x-, y-, width- und height-Attribute des Filters an. Optionaler Parameter. |
| primitiveUnits | Gibt das Koordinatensystem für die Attribute der Kind-Elemente des Filters an. Optionaler Parameter. |
| x | Die x‑Koordinate des Filterbereichs. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y‑Koordinate des Filterbereichs. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Filterbereichs. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Filterbereichs. Kann ein Double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fill | Die Füllfarbe oder das Fill für das Filter-Element. Optionaler Parameter. |
| stroke | Die Strichfarbe oder das Stroke für das Filter-Element. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Filter-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGFilterElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
