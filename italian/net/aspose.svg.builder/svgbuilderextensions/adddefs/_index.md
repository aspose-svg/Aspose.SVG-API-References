---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddDefs. Aggiunge una configurazione dell'elemento defs al builder."
type: docs
weight: 100
url: /it/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

Aggiunge una configurazione dell'elemento 'defs' (definizioni) al costruttore.

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'defs'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
