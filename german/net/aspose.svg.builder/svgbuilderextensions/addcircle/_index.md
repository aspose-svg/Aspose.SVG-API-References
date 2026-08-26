---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddCircle-Methode. Fügt dem Builder eine Kreis-Elementkonfiguration hinzu."
type: docs
weight: 70
url: /de/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Fügt dem Builder eine 'circle'‑Elementkonfiguration hinzu.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'circle'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Fügt dem SVG‑Builder ein 'circle'‑Element mit angegebenem Mittelpunkt, Radius und Stilen hinzu.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'circle'-Element hinzugefügt wird. |
| cx | Die x-Koordinate des Kreismittelpunkts. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| cy | Die y-Koordinate des Kreismittelpunkts. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| r | Der Radius des Kreises. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| fill | Die Füllfarbe oder der Malstil für den Kreis. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für die Kontur des Kreises. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Kreiselement. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Builder des Kreiselements weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
