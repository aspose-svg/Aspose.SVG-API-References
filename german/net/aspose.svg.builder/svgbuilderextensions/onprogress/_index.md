---
title: "SVGBuilderExtensions.OnProgress"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnProgress-Methode. Setzt das onprogress-Event-Attribut zum Verarbeiten von Ereignissen, die den Fortschritt eines laufenden Vorgangs anzeigen"
type: docs
weight: 1680
url: /de/net/aspose.svg.builder/svgbuilderextensions/onprogress/
---
## SVGBuilderExtensions.OnProgress<TBuilder> method

Setzt das Attribut 'onprogress' für die Behandlung von Ereignissen, die den Fortschritt eines laufenden Prozesses anzeigen.

```csharp
public static TBuilder OnProgress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript‑Funktion oder das Skript, das ausgeführt wird, um den Fortschritt eines laufenden Vorgangs anzuzeigen. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
