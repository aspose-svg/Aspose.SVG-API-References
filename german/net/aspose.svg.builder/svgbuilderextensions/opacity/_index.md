---
title: "SVGBuilderExtensions.Opacity"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Opacity-Methode. Setzt das opacity-Attribut für ein SVG-Element, das dessen Transparenzgrad definiert."
type: docs
weight: 1860
url: /de/net/aspose.svg.builder/svgbuilderextensions/opacity/
---
## SVGBuilderExtensions.Opacity<TBuilder> method

Setzt das 'opacity'-Attribut für ein SVG-Element und definiert dessen Transparenzstufe.

```csharp
public static TBuilder Opacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| opacity | Der Opazitätswert (0,0 für vollständig transparent, 1,0 für vollständig undurchsichtig). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
