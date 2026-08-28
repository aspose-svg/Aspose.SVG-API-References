---
title: "SVGBuilderExtensions.AddContent"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddContent. Aggiunge contenuto testuale all'elemento SVG"
type: docs
weight: 90
url: /it/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Aggiunge contenuto testuale all'elemento SVG.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| testo | Il testo da aggiungere all'elemento. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

## Osservazioni

Questo metodo consente di aggiungere contenuto testuale direttamente a un elemento SVG. È utile per gli elementi che contengono dati testuali.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
