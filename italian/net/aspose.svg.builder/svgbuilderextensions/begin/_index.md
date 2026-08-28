---
title: "SVGBuilderExtensions.Begin"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Begin. Imposta l'attributo begin che definisce quando l'animazione dovrebbe iniziare."
type: docs
weight: 610
url: /it/net/aspose.svg.builder/svgbuilderextensions/begin/
---
## SVGBuilderExtensions.Begin<TBuilder> method

Imposta l'attributo 'begin', definendo quando l'animazione dovrebbe iniziare.

```csharp
public static TBuilder Begin<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| configurare | Un delegato per configurare il valore di temporizzazione. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
