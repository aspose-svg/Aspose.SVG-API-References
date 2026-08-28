---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions StrokeDashoffset. Imposta l'attributo stroke-dashoffset per un elemento SVG definendo lo spostamento per l'inizio dell'array di dash del tratto"
type: docs
weight: 2100
url: /it/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

Imposta l'attributo 'stroke-dashoffset' per un elemento SVG, definendo lo spostamento per l'inizio dell'array di tratteggi del tratto.

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | Il valore dello spostamento dash. |
| tipo | Il tipo di unità per il valore dello spostamento. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
