---
title: "SVGBuilderExtensions.By"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions By. Imposta l'attributo by che definisce il valore di offset relativo per l'animazione con un tipo di lunghezza specificato"
type: docs
weight: 620
url: /it/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Imposta l'attributo 'by', definendo il valore di offset relativo per l'animazione con un tipo di lunghezza specificato.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il valore di offset relativo per l'animazione. |
| tipo | Il tipo di lunghezza per il valore 'by'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
