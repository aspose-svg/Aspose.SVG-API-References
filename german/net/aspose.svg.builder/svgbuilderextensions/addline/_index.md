---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddLine-Methode. Fügt dem Builder eine Konfiguration für ein Linien‑Element hinzu"
type: docs
weight: 350
url: /de/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Fügt dem Builder eine 'line'-Elementkonfiguration hinzu.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'line'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Fügt dem SVG-Builder ein 'line'-Element mit angegebenen Start- und Endpunkten sowie Stilen hinzu.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'line'-Element hinzugefügt wird. |
| x1 | Die x‑Koordinate des Startpunkts der Linie. Kann ein double‑Wert oder ein Tupel aus double und LengthType sein. |
| y1 | Die y‑Koordinate des Startpunkts der Linie. Kann ein double‑Wert oder ein Tupel aus double und LengthType sein. |
| x2 | Die x-Koordinate des Endpunkts der Linie. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| y2 | Die y-Koordinate des Endpunkts der Linie. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| fill | Die Füllfarbe oder der Malstil für die Linie. Kann ein Color oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für die Linie. Kann ein Color oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Linienelement. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Builder des Linienelements weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
