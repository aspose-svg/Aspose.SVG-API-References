---
title: "SVGBuilderExtensions.AddSvg"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddSvg. Aggiunge una configurazione di elemento svg (grafica vettoriale scalabile) al builder."
type: docs
weight: 500
url: /it/net/aspose.svg.builder/svgbuilderextensions/addsvg/
---
## SVGBuilderExtensions.AddSvg<TBuilder> method

Aggiunge una configurazione dell'elemento 'svg' (grafica vettoriale scalabile) al costruttore.

```csharp
public static TBuilder AddSvg<TBuilder>(this TBuilder builder, 
    Action<SVGSVGElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'svg'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGSVGElementBuilder](../../svgsvgelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
