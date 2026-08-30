---
title: "SVGBuilderExtensions.OnProgress"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnProgress‑metoden. Ställer in onprogress‑händelseattributet för att hantera händelser som indikerar framsteg i en pågående process."
type: docs
weight: 1680
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onprogress/
---
## SVGBuilderExtensions.OnProgress<TBuilder> method

Anger 'onprogress' eventattributet för att hantera händelser som visar framsteg i en pågående process.

```csharp
public static TBuilder OnProgress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras för att indikera framsteg i en pågående process. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
