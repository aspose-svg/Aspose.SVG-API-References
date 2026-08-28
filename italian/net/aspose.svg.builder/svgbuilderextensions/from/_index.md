---
title: "SVGBuilderExtensions.From"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo From di SVGBuilderExtensions. Imposta l'attributo from definendo il valore iniziale dell'animazione con un tipo di lunghezza specificato."
type: docs
weight: 960
url: /it/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

Imposta l'attributo 'from', definendo il valore iniziale dell'animazione con un tipo di lunghezza specificato.

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il valore iniziale per l'animazione. |
| tipo | Il tipo di lunghezza per il valore 'from'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
