---
title: "SVGBuilderExtensions.ClipPath"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions ClipPath-Methode. Setzt das clip-path-Attribut für ein SVG-Element"
type: docs
weight: 650
url: /de/net/aspose.svg.builder/svgbuilderextensions/clippath/
---
## SVGBuilderExtensions.ClipPath<TBuilder> method

Setzt das Attribut 'clip-path' für ein SVG-Element.

```csharp
public static TBuilder ClipPath<TBuilder>(this TBuilder builder, Action<ClipPathBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Ein Delegat zum Konfigurieren des Clip-Pfads. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [ClipPathBuilder](../../clippathbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
