---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions OnAbort‑metod. Ställer in onabort‑händelseattributet som definierar ett skript att köra när inläsning av ett SVG-dokument avbryts."
type: docs
weight: 1190
url: /sv/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

Ställer in händelseattributet 'onabort' och definierar ett skript som körs när inläsningen av ett SVG-dokument avbryts.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | SVG-elementbyggaren. |
| value | JavaScript‑funktionen eller skriptet som ska köras när dokumentets inläsning avbryts. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
