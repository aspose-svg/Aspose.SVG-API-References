---
title: "SVGBuilderExtensions.StopColor"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions StopColor-Methode. Setzt das stop-color-Attribut für ein SVG-Element, das die Farbe an einem Farbverlaufs-Stopp definiert."
type: docs
weight: 2060
url: /de/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

Setzt das Attribut 'stop-color' für ein SVG-Element und definiert die Farbe an einem Farbverlauf-Stopp.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| colorValue | Der zu setzende Farbwert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Setzt das Attribut 'stop-color' für ein SVG-Element unter Verwendung einer benutzerdefinierten Farbkonfiguration.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Ein Delegat zum Konfigurieren der Farbe. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
