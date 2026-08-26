---
title: "SVGBuilderExtensions.FloodColor"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions FloodColor method. Setzt das flood-color-Attribut für ein SVG-Element unter Verwendung einer System.Drawing-Farbe."
type: docs
weight: 850
url: /de/net/aspose.svg.builder/svgbuilderextensions/floodcolor/
---
## FloodColor<TBuilder>(*this TBuilder, Color*) {#floodcolor_1}

Setzt das Attribut 'flood-color' für ein SVG-Element mit einer System.Drawing-Farbe.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| colorValue | Die Farbe, die als Flood-Color gesetzt werden soll. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FloodColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#floodcolor}

Setzt das Attribut 'flood-color' für ein SVG-Element mit einer benutzerdefinierten Farbkonfiguration.

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Ein Delegat zum Konfigurieren des ColorBuilder. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
