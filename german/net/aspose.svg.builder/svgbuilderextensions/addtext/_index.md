---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddText‑Methode. Fügt dem Builder eine Text‑Element‑Konfiguration hinzu."
type: docs
weight: 530
url: /de/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Fügt dem Builder eine Konfiguration für das 'text'-Element hinzu.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'text'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Fügt dem SVG-Builder ein 'text'-Element mit angegebenem Inhalt und Attributen hinzu.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der Verkettung ermöglicht. |
| builder | Die Builder-Instanz, zu der das 'text'-Element hinzugefügt wird. |
| Inhalt | Der Textinhalt, der innerhalb des 'text'-Elements angezeigt wird. |
| x | Die x-Koordinate für das Textelement. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| y | Die y-Koordinate für das Textelement. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| Schriftgröße | Die Schriftgröße für den Text. Kann ein double-Wert oder ein Tupel aus double und LengthType sein. |
| Schriftstil | Der Schriftstil für den Text (z. B. normal, italic, oblique). |
| Schriftfamilie | Die Schriftfamilie für den Text (z. B. Arial, Verdana). |
| Schriftgewicht | Das Gewicht (Dicke) der Schrift (z. B. normal, bold). |
| fill | Die Füllfarbe oder der Malstil für den Text. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. |
| stroke | Die Konturfarbe oder der Malstil für den Text. Kann ein Color- oder ein Paint-Enum-Wert oder eine Paint-Server-ID sein. |
| id | Der eindeutige Bezeichner für das Textelement. |
| extend | Eine optionale Aktion, um den Text-Element-Builder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz zum Verketteln weiterer Ergänzungen oder Konfigurationen.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
