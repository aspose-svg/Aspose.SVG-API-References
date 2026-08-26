---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions SetPreserveAspectRatio-Methode. Legt das Attribut preserveAspectRatio für ein SVG-Element fest."
type: docs
weight: 2020
url: /de/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Setzt das 'preserveAspectRatio'-Attribut für ein SVG-Element.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| align | Die Ausrichtungseinstellung für das Seitenverhältnis. |
| meetOrSlice | Gibt an, wie ein Seitenverhältnis beibehalten wird (Standard ist 'Meet'). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
