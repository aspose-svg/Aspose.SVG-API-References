---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddRadialGradient Methode. Fügt eine radialGradient-Elementkonfiguration zum Builder hinzu."
type: docs
weight: 440
url: /de/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Fügt dem Builder eine Konfiguration für das 'radialGradient'-Element hinzu.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'radialGradient'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Fügt dem SVG-Builder ein 'radialGradient'-Element hinzu und gibt dessen Mittelpunkt, Radius und Brennpunkte sowie weitere Gradienteneigenschaften an.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'radialGradient'-Element hinzugefügt wird. |
| cx | Die x-Koordinate des Zentrums des Farbverlaufs. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| cy | Die y-Koordinate des Zentrums des Farbverlaufs. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| r | Der Radius des Farbverlaufs. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fx | Die x-Koordinate des Brennpunkts des Farbverlaufs. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| fy | Die y-Koordinate des Brennpunkts des Farbverlaufs. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| gradientUnits | Gibt das Koordinatensystem für den Farbverlauf an. Optionaler Parameter. |
| spreadMethod | Definiert, wie sich der Farbverlauf über seine Start- und Endpunkte hinaus ausbreitet. Optionaler Parameter. |
| href | Der Verweis auf einen anderen Farbverlauf, falls zutreffend. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Farbverlaufs-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den radialen Farbverlaufs-Element-Builder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
