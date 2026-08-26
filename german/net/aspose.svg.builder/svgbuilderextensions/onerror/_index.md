---
title: "SVGBuilderExtensions.OnError"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnError-Methode. Setzt das onerror-Ereignisattribut zur Behandlung von Fehlerereignissen am Element."
type: docs
weight: 1430
url: /de/net/aspose.svg.builder/svgbuilderextensions/onerror/
---
## SVGBuilderExtensions.OnError<TBuilder> method

Legt das 'onerror'-Ereignisattribut fest, um Fehlerereignisse auf dem Element zu behandeln.

```csharp
public static TBuilder OnError<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, ICommonEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das ausgeführt wird, wenn ein Fehler auftritt. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICommonEventAttributeSetter](../../icommoneventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
