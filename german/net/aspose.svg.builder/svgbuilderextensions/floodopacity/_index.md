---
title: "SVGBuilderExtensions.FloodOpacity"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions FloodOpacity‑Methode. Setzt das flood-opacity‑Attribut für ein SVG‑Element. Der Wert muss zwischen 0,0 (vollständig transparent) und 1,0 (vollständig undurchsichtig) liegen."
type: docs
weight: 860
url: /de/net/aspose.svg.builder/svgbuilderextensions/floodopacity/
---
## SVGBuilderExtensions.FloodOpacity<TBuilder> method

Setzt das Attribut 'flood-opacity' für ein SVG-Element. Der Wert muss zwischen 0,0 (vollständig transparent) und 1,0 (vollständig undurchsichtig) liegen.

```csharp
public static TBuilder FloodOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| opacity | Der zu setzende Opazitätswert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Wird ausgelöst, wenn die Opazität nicht im gültigen Bereich liegt. |

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
