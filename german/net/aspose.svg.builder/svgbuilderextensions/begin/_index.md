---
title: "SVGBuilderExtensions.Begin"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Begin Methode. Setzt das begin-Attribut, das definiert, wann die Animation starten soll."
type: docs
weight: 610
url: /de/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Setzt das Attribut 'begin' und definiert, wann die Animation starten soll.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
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
