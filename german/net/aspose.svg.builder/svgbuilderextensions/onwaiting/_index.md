---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnWaiting-Methode. Setzt das onwaiting-Ereignisattribut zur Behandlung von Ereignissen, wenn die Medienwiedergabe aufgrund von Datenpufferung verzögert wird"
type: docs
weight: 1850
url: /de/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

Setzt das 'onwaiting'-Ereignisattribut, um Ereignisse zu behandeln, wenn die Medienwiedergabe aufgrund von Datenpufferung verzögert wird.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript‑Funktion oder das Skript, das ausgeführt wird, wenn die Medienwiedergabe zum Puffern verzögert wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
