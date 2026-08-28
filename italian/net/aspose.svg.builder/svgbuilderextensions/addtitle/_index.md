---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddTitle. Aggiunge una configurazione dell'elemento title al builder. L'elemento title è usato per fornire un titolo al contenuto SVG."
type: docs
weight: 540
url: /it/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

Aggiunge una configurazione dell'elemento 'title' al costruttore. L'elemento 'title' è usato per fornire un titolo al contenuto SVG.

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'title'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
