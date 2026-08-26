---
title: "SVGBuilderExtensions.LightingColor"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions LightingColor Methode. Setzt das lighting-color-Attribut für ein SVG-Element unter Verwendung eines angegebenen Farbwertes."
type: docs
weight: 1110
url: /de/net/aspose.svg.builder/svgbuilderextensions/lightingcolor/
---
## LightingColor<TBuilder>(*this TBuilder, Color*) {#lightingcolor_1}

Setzt das Attribut 'lighting-color' für ein SVG-Element mit einem angegebenen Farbwert.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| colorValue | Der Farbwert, der für den Lichteffekt gesetzt wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LightingColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#lightingcolor}

Setzt das Attribut 'lighting-color' für ein SVG-Element unter Verwendung einer benutzerdefinierten Farbkombination.

```csharp
public static TBuilder LightingColor<TBuilder>(this TBuilder builder, 
    Action<ColorBuilder> configure)
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
