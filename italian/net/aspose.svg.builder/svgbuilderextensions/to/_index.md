---
title: "SVGBuilderExtensions.To"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo To di SVGBuilderExtensions. Imposta l'attributo to che definisce il valore finale dell'animazione con un tipo di lunghezza specificato."
type: docs
weight: 2250
url: /it/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Imposta l'attributo 'to', definendo il valore finale dell'animazione con un tipo di lunghezza specificato.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il valore finale per l'animazione. |
| tipo | Il tipo di lunghezza per il valore 'to'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
