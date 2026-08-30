---
title: "SVGBuilderExtensions.OnCut"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnCut-metod. Ställer in oncut‑händelseattributet som definierar ett skript som ska köras när innehåll klipps från SVG‑elementet."
type: docs
weight: 1290
url: /sv/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

Ställer in 'oncut'-händelseattributet, vilket definierar ett skript som körs när innehåll klipps från SVG-elementet.

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras vid klipp‑händelsen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
