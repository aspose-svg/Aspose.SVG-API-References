---
title: "SVGBuilderExtensions.OnStalled"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnStalled-metod. Ställer in onstalled-händelseattributet för att hantera händelser när mediadataöverföring oväntat stoppas."
type: docs
weight: 1780
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onstalled/
---
## SVGBuilderExtensions.OnStalled<TBuilder> method

Anger 'onstalled' eventattributet för att hantera händelser när mediadataöverföring oväntat stoppas.

```csharp
public static TBuilder OnStalled<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras när mediedatatransferensen stannar. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
