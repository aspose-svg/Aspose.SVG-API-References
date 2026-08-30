---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnFocusIn‑metod. Ställer in onfocusin‑händelseattributet för att hantera fokus‑in‑händelser på elementet"
type: docs
weight: 1450
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Ställer in 'onfocusin'-händelseattributet för att hantera fokus-in-händelser på elementet.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras när elementet får fokus, vanligtvis före 'onfocus'-händelsen. |

### Returvärde

Byggarinstansen för kedjning.

## Anmärkningar

'onfocusin'-händelsen utlöses när ett element är på väg att få fokus. Denna händelse skiljer sig från 'onfocus' genom att den stödjer bubbling och kan även användas för att upptäcka fokusändringar på underordnade element.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
