---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddLinearGradient method. Fügt dem Builder eine linearGradient-Elementkonfiguration hinzu."
type: docs
weight: 360
url: /de/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Fügt dem Builder eine 'linearGradient'-Elementkonfiguration hinzu.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'linearGradient'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Fügt dem SVG-Builder ein 'linearGradient'-Element hinzu, das seine Start- und Endpositionen sowie weitere Gradienteneigenschaften festlegt.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'linearGradient'-Element hinzugefügt wird. |
| x1 | Die Start-x-Koordinate für den Farbverlauf. Kann ein double oder ein ValueTuple mit LengthType sein. |
| y1 | Die y-Startkoordinate für den Farbverlauf. Kann ein double oder ein ValueTuple mit LengthType sein. |
| x2 | Die x-Endkoordinate für den Farbverlauf. Kann ein double oder ein ValueTuple mit LengthType sein. |
| y2 | Die y-Endkoordinate für den Farbverlauf. Kann ein double oder ein ValueTuple mit LengthType sein. |
| gradientUnits | Gibt das Koordinatensystem für den Farbverlauf an. Optionaler Parameter. |
| spreadMethod | Definiert, wie sich der Farbverlauf über seine Start- und Endpunkte hinaus ausbreitet. Optionaler Parameter. |
| href | Der Verweis auf einen anderen Farbverlauf, falls zutreffend. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Farbverlaufs-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Builder für lineare Farbverlauf-Elemente weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
