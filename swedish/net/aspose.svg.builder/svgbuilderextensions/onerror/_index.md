---
title: "SVGBuilderExtensions.OnError"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnError‑metod. Ställer in onerror‑händelseattributet för att hantera felhändelser på elementet."
type: docs
weight: 1430
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onerror/
---
## SVGBuilderExtensions.OnError<TBuilder> method

Ställer in 'onerror'-händelseattributet för att hantera felhändelser på elementet.

```csharp
public static TBuilder OnError<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, ICommonEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras när ett fel inträffar. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICommonEventAttributeSetter](../../icommoneventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
