---
title: "SVGBuilderExtensions.OnPaste"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnPaste-metod. Ställer in onpaste‑händelseattributet som definierar ett skript att köra när innehåll klistras in i SVG‑elementet"
type: docs
weight: 1640
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onpaste/
---
## SVGBuilderExtensions.OnPaste<TBuilder> method

Anger 'onpaste' eventattributet, som definierar ett skript som körs när innehåll klistras in i SVG-elementet.

```csharp
public static TBuilder OnPaste<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras vid klistra‑in‑händelsen. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
