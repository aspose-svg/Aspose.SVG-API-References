---
title: "SVGBuilderExtensions.TextLength"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo TextLength di SVGBuilderExtensions. Imposta la lunghezza esatta del contenuto testuale"
type: docs
weight: 2220
url: /it/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

Imposta la lunghezza esatta del contenuto testuale.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La lunghezza del testo. |
| tipo | Il tipo di unità di lunghezza per il valore. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'textLength', specificando la lunghezza desiderata del contenuto testuale, potenzialmente sovrascrivendo la lunghezza naturale del testo.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
