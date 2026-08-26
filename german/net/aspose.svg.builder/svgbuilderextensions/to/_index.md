---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions To-Methode. Setzt das to-Attribut, das den Endwert der Animation mit einem angegebenen Längentyp definiert."
type: docs
weight: 2250
url: /de/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Setzt das Attribut 'to' und definiert den Endwert der Animation mit einem angegebenen Längentyp.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Der Endwert für die Animation. |
| type | Der Längentyp für den 'to'-Wert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
