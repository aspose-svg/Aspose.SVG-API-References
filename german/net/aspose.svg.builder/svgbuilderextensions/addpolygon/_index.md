---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddPolygon-Methode. Fügt dem Builder eine Polygon-Elementkonfiguration hinzu."
type: docs
weight: 420
url: /de/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Fügt dem Builder eine Konfiguration für das 'polygon'-Element hinzu.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'polygon'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Fügt dem SVG-Builder ein 'polygon'-Element hinzu und gibt dessen Eckpunkte und Stile an.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'polygon'-Element hinzugefügt wird. |
| points | Ein Array von Doubles, das die Punkte des Polygons darstellt (abwechselnde x- und y-Koordinaten). |
| fill | Die Füllfarbe oder der Malstil für das Polygon. Kann ein Color oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für das Polygon. Kann ein Color oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Polygon-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Polygon-Element-Builder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
