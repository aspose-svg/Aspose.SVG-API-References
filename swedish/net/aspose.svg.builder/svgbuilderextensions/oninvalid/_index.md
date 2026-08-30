---
title: "SVGBuilderExtensions.OnInvalid"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnInvalid-metoden. Ställer in oninvalid‑händelseattributet för att hantera ogiltiga händelser på formulärelement."
type: docs
weight: 1480
url: /sv/net/aspose.svg.builder/svgbuilderextensions/oninvalid/
---
## SVGBuilderExtensions.OnInvalid<TBuilder> method

Ställer in 'oninvalid'-händelseattributet för att hantera ogiltiga händelser på formulärelement.

```csharp
public static TBuilder OnInvalid<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript-funktionen eller skriptet som ska köras när elementets värde är ogiltigt. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
