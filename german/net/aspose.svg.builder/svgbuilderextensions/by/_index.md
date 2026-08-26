---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions By-Methode. Setzt das by-Attribut, das den relativen Versatzwert für die Animation mit einem angegebenen Längentyp definiert."
type: docs
weight: 620
url: /de/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Setzt das Attribut 'by' und definiert den relativen Versatzwert für die Animation mit einem angegebenen Längentyp.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Der relative Versatzwert für die Animation. |
| type | Der Längentyp für den 'by'-Wert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
