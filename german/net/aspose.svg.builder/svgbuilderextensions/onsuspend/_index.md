---
title: "SVGBuilderExtensions.OnSuspend"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnSuspend-Methode. Legt das onsuspend-Ereignisattribut fest, um Ereignisse zu behandeln, wenn das Laden von Mediendaten ausgesetzt wird."
type: docs
weight: 1800
url: /de/net/aspose.svg.builder/svgbuilderextensions/onsuspend/
---
## SVGBuilderExtensions.OnSuspend<TBuilder> method

Setzt das Attribut 'onsuspend' für die Behandlung von Ereignissen, wenn das Laden von Mediendaten ausgesetzt wird.

```csharp
public static TBuilder OnSuspend<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript‑Funktion oder das Skript, das ausgeführt wird, wenn das Laden von Mediendaten ausgesetzt ist. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
