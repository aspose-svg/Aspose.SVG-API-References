---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddFeMerge. Aggiunge una configurazione dell'elemento feMerge al builder. Questo elemento consente di applicare gli effetti filtro in modo concorrente anziché sequenziale"
type: docs
weight: 240
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

Aggiunge una configurazione dell'elemento 'feMerge' al builder. Questo elemento consente di applicare gli effetti del filtro in modo concorrente anziché sequenziale.

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'feMerge'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
