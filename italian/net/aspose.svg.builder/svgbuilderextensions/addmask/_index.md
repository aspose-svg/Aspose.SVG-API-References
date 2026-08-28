---
title: "SVGBuilderExtensions.AddMask"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddMask. Aggiunge una configurazione dell'elemento mask al builder"
type: docs
weight: 380
url: /it/net/aspose.svg.builder/svgbuilderextensions/addmask/
---
## SVGBuilderExtensions.AddMask<TBuilder> method

Aggiunge una configurazione dell'elemento 'mask' al costruttore.

```csharp
public static TBuilder AddMask<TBuilder>(this TBuilder builder, 
    Action<SVGMaskElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'mask'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGMaskElementBuilder](../../svgmaskelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
