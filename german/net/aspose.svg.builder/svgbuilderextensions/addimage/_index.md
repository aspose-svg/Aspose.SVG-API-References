---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddImage-Methode. Fügt eine Bild-Element-Konfiguration zum Builder hinzu."
type: docs
weight: 330
url: /de/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Fügt dem Builder eine 'image'-Elementkonfiguration hinzu.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'image'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

Fügt dem SVG-Builder ein 'image'-Element hinzu, das ein externes Bild in das SVG-Dokument einbettet.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG-Builder-Instanz, zu der das 'image'-Element hinzugefügt wird. |
| href | Die URL oder Referenz zum externen Bild. Optionaler Parameter. |
| x | Die x-Koordinate, an der das Bild platziert wird. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| y | Die y-Koordinate, an der das Bild platziert wird. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| width | Die Breite des Bildes. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| height | Die Höhe des Bildes. Kann ein double oder ein ValueTuple mit LengthType sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Bild-Element. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den SVGImageElementBuilder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
