---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo KeySplines di SVGBuilderExtensions. Imposta l'attributo keySplines specificando i punti di controllo per il ritmo dell'animazione"
type: docs
weight: 1060
url: /it/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Imposta l'attributo 'keySplines', specificando i punti di controllo per il ritmo dell'animazione.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| buildSplines | L'azione per costruire la configurazione della spline. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
