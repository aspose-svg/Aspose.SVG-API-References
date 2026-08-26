---
title: "SVGBuilderExtensions.StrokeWidth"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions StrokeWidth-Methode. Legt das stroke-width-Attribut für ein SVG-Element fest, das die Breite des Strichs definiert."
type: docs
weight: 2150
url: /de/net/aspose.svg.builder/svgbuilderextensions/strokewidth/
---
## SVGBuilderExtensions.StrokeWidth<TBuilder> method

Setzt das Attribut 'stroke-width' für ein SVG-Element und definiert die Breite der Kontur.

```csharp
public static TBuilder StrokeWidth<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Strichbreitenwert. |
| type | Der Einheitstyp für die Strichbreite. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
