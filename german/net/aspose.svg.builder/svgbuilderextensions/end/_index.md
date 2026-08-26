---
title: "SVGBuilderExtensions.End"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions End-Methode. Setzt das end-Attribut, das definiert, wann die Animation enden soll."
type: docs
weight: 790
url: /de/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

Setzt das Attribut 'end' und definiert, wann die Animation enden soll.

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| konfigurieren | Ein Delegat zur Konfiguration des Zeitwertes. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
