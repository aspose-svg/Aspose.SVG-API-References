---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnFocusOut‑metod. Ställer in onfocusout‑händelseattributet för att hantera fokus‑ut‑händelser på elementet."
type: docs
weight: 1460
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Ställer in 'onfocusout'-händelseattributet för att hantera fokus-ut-händelser på elementet.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras när elementet förlorar fokus, vanligtvis före 'onblur'-händelsen. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

'onfocusout'-händelsen utlöses när ett element är på väg att förlora fokus. Liknande 'onfocusin' stödjer denna händelse bubbling och kan även användas för att upptäcka fokusändringar på underordnade element.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
