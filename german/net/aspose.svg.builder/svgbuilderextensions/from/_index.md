---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions From-Methode. Setzt das from-Attribut, das den Startwert der Animation mit einem angegebenen Längentyp definiert."
type: docs
weight: 960
url: /de/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Setzt das Attribut 'from' und definiert den Startwert der Animation mit einem angegebenen Längentyp.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Der Startwert für die Animation. |
| type | Der Längentyp für den 'from'-Wert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
