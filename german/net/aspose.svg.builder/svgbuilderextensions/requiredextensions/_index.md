---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions RequiredExtensions-Methode. Setzt das requiredExtensions-Attribut auf dem SVG-Element. Dieses Attribut gibt an, welche Erweiterungen für die Verarbeitung des SVG-Dokumentfragments erforderlich sind."
type: docs
weight: 1970
url: /de/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

Setzt das 'requiredExtensions'-Attribut am SVG-Element. Dieses Attribut gibt an, welche Erweiterungen für die Verarbeitung des SVG-Dokumentfragments erforderlich sind.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder, an dem das Attribut gesetzt wird. |
| value | Ein Zeichenkettenwert, der die erforderlichen Erweiterungen darstellt. |

### Rückgabewert

Der ursprüngliche SVG-Element-Builder für Methodenverkettung.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
