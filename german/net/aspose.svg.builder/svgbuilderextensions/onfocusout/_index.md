---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnFocusOut‑Methode. Setzt das onfocusout‑Event‑Attribut zur Behandlung von Fokus‑Verlust‑Ereignissen auf dem Element."
type: docs
weight: 1460
url: /de/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Legt das 'onfocusout'-Ereignisattribut fest, um Fokus‑Austritts‑Ereignisse auf dem Element zu behandeln.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript‑Funktion oder das Skript, das ausgeführt wird, wenn das Element den Fokus verliert, typischerweise vor dem 'onblur'-Ereignis. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Das 'onfocusout'-Ereignis wird ausgelöst, wenn ein Element kurz davor ist, den Fokus zu verlieren. Ähnlich wie 'onfocusin' unterstützt dieses Ereignis das Bubbling und kann ebenfalls verwendet werden, um Fokusänderungen bei Kind‑Elementen zu erkennen.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
