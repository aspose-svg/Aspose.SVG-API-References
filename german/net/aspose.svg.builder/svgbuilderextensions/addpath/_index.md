---
title: "SVGBuilderExtensions.AddPath"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddPath Methode. Fügt dem Builder eine Pfadelement‑Konfiguration hinzu."
type: docs
weight: 400
url: /de/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

Fügt dem Builder eine Konfiguration für das 'path'-Element hinzu.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'path'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

Fügt dem SVG-Builder ein 'path'-Element hinzu und gibt dessen Pfaddaten und Stile an.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'path'-Element hinzugefügt wird. |
| d | Ein OneOf‑Typ, der entweder ein String ist, der die Pfaddaten darstellt, oder eine Aktion, die einen PathBuilder konfiguriert. |
| fill | Die Füllfarbe oder der Malstil für den Pfad. Kann ein Color‑ oder Paint‑Enum‑Wert oder eine Paint‑Server‑ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für den Pfad. Kann ein Color‑ oder Paint‑Enum‑Wert oder eine Paint‑Server‑ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Pfadelement. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Pfadelement‑Builder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

Überladung von AddPath, die eine Aktion entgegennimmt, um einen PathBuilder direkt zu konfigurieren.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders, der die Verwendung einer flüssigen API erleichtert. |
| builder | Die SVG‑Builder‑Instanz, zu der das 'path'-Element hinzugefügt wird. |
| d | Eine Aktion, die einen PathBuilder konfiguriert, um die Pfaddaten zu definieren. |
| fill | Die Füllfarbe oder der Malstil für den Pfad. Kann ein Color‑ oder Paint‑Enum‑Wert oder eine Paint‑Server‑ID sein. Optionaler Parameter. |
| stroke | Die Strichfarbe oder der Malstil für den Pfad. Kann ein Color‑ oder Paint‑Enum‑Wert oder eine Paint‑Server‑ID sein. Optionaler Parameter. |
| id | Der eindeutige Bezeichner für das Pfadelement. Optionaler Parameter. |
| extend | Eine optionale Aktion, um den Pfadelement‑Builder weiter zu konfigurieren. |

### Rückgabewert

Die Builder-Instanz, die Methodenkettung ermöglicht.

### Siehe auch

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
