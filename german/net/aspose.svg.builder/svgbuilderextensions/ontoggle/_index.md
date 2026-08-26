---
title: "SVGBuilderExtensions.OnToggle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnToggle-Methode. Setzt das ontoggle-Ereignisattribut zur Behandlung von Ereignissen, wenn der Benutzer ein Steuerelement wie ein details-Element umschaltet."
type: docs
weight: 1820
url: /de/net/aspose.svg.builder/svgbuilderextensions/ontoggle/
---
## SVGBuilderExtensions.OnToggle<TBuilder> method

Setzt das Attribut 'ontoggle' für die Behandlung von Ereignissen, wenn der Benutzer ein Steuerelement umschaltet, wie ein `details`‑Element.

```csharp
public static TBuilder OnToggle<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das ausgeführt wird, wenn ein Steuerelement umgeschaltet wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
