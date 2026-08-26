---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddRect-Methode. Fügt dem Builder eine Konfiguration für ein rect-Element hinzu"
type: docs
weight: 450
url: /de/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Fügt dem Builder eine Konfiguration für das 'rect'-Element hinzu.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'rect'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Fügt dem SVG-Builder ein 'rect' (Rechteck)-Element mit angegebenen Abmessungen und Stilen hinzu.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'rect'-Element hinzugefügt wird. |
| x | Die x-Koordinate des Startpunkts des Rechtecks. Kann ein Double-Wert oder ein Tupel aus Double und LengthType sein. |
| y | Die y-Koordinate des Startpunkts des Rechtecks. Kann ein Double-Wert oder ein Tupel aus Double und LengthType sein. |
| width | Die Breite des Rechtecks. Kann ein Double-Wert oder ein Tupel aus Double und LengthType sein. |
| height | Die Höhe des Rechtecks. Kann ein Double-Wert oder ein Tupel aus Double und LengthType sein. |
| fill | Die Füllfarbe oder der Malstil für das Rechteck. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für die Kontur des Rechtecks. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Rechteckelement. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Builder des Rechteckelements weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
