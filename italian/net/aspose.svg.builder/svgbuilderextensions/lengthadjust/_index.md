---
title: "SVGBuilderExtensions.LengthAdjust"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions LengthAdjust. Imposta il metodo di aggiustamento della lunghezza per il contenuto del testo"
type: docs
weight: 1090
url: /it/net/aspose.svg.builder/svgbuilderextensions/lengthadjust/
---
## SVGBuilderExtensions.LengthAdjust<TBuilder> method

Imposta il metodo di regolazione della lunghezza per il contenuto testuale.

```csharp
public static TBuilder LengthAdjust<TBuilder>(this TBuilder builder, LengthAdjust value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | Il metodo di aggiustamento della lunghezza. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo imposta l'attributo 'lengthAdjust', determinando come la lunghezza del testo viene aggiustata, sia tramite spaziatura che tramite scaling.

### Vedi anche

* enum [LengthAdjust](../../lengthadjust/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
