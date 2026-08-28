---
title: "SVGBuilderExtensions.AddView"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddView. Aggiunge una configurazione dell'elemento view al costruttore."
type: docs
weight: 560
url: /it/net/aspose.svg.builder/svgbuilderextensions/addview/
---
## SVGBuilderExtensions.AddView<TBuilder> method

Aggiunge una configurazione dell'elemento 'view' al costruttore.

```csharp
public static TBuilder AddView<TBuilder>(this TBuilder builder, 
    Action<SVGViewElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'view'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGViewElementBuilder](../../svgviewelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
