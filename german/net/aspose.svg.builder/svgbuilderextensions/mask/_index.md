---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Mask-Methode. Setzt das mask-Attribut für ein SVG‑Element unter Verwendung einer benutzerdefinierten Maskenkonfiguration"
type: docs
weight: 1150
url: /de/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Setzt das Attribut 'mask' für ein SVG-Element unter Verwendung einer benutzerdefinierten Maskenkonfiguration.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Ein Delegat zum Konfigurieren der Maske. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
