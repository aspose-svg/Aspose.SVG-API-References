---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions StrokeDashoffset-Methode. Setzt das Attribut stroke-dashoffset für ein SVG-Element und definiert den Versatz für den Beginn des Strichpunkt-Arrays."
type: docs
weight: 2100
url: /de/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

Setzt das Attribut 'stroke-dashoffset' für ein SVG-Element und definiert den Versatz für den Beginn des Strichmuster-Arrays.

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Strichversatzwert. |
| type | Der Einheitstyp für den Versatzwert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
