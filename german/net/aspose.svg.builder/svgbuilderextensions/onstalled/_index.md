---
title: "SVGBuilderExtensions.OnStalled"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnStalled-Methode. Setzt das onstalled-Event-Attribut für die Behandlung von Ereignissen, wenn die Medien-Datenübertragung unerwartet unterbrochen wird."
type: docs
weight: 1780
url: /de/net/aspose.svg.builder/svgbuilderextensions/onstalled/
---
## SVGBuilderExtensions.OnStalled<TBuilder> method

Setzt das Attribut 'onstalled' für die Behandlung von Ereignissen, wenn die Medien‑Datenübertragung unerwartet gestoppt wird.

```csharp
public static TBuilder OnStalled<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das ausgeführt wird, wenn die Medien-Datenübertragung stockt. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
