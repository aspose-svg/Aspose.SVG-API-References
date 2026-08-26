---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddPolyline-Methode. Fügt dem Builder eine Polyline-Elementkonfiguration hinzu."
type: docs
weight: 430
url: /de/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Fügt dem Builder eine Konfiguration für das 'polyline'-Element hinzu.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'polyline'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Fügt dem SVG-Builder ein 'polyline'-Element hinzu und gibt dessen Eckpunkte und Stile an.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'polyline'-Element hinzugefügt wird. |
| points | Ein Array von Double-Werten, das die Punkte der Polyline darstellt (abwechselnde x- und y-Koordinaten). |
| fill | Die Füllfarbe oder der Malstil für die Polyline. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für die Polyline. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Polyline-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Polyline-Element-Builder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
