---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo TextDecoration di SVGBuilderExtensions. Imposta l'attributo text-decoration per un elemento SVG definendo le decorazioni aggiunte al testo"
type: docs
weight: 2210
url: /it/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Imposta l'attributo 'text-decoration' per un elemento SVG, definendo le decorazioni che vengono aggiunte al testo.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| underline | Specifica se il testo deve essere sottolineato. |
| overline | Specifica se il testo deve avere una sovralineatura. |
| lineThrough | Specifica se il testo deve avere una linea attraverso di esso. |
| blink | Specifica se il testo deve lampeggiare (non consigliato). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
