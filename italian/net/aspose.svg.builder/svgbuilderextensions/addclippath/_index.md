---
title: "SVGBuilderExtensions.AddClipPath"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddClipPath di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento clipPath al builder"
type: docs
weight: 80
url: /it/net/aspose.svg.builder/svgbuilderextensions/addclippath/
---
## SVGBuilderExtensions.AddClipPath<TBuilder> method

Aggiunge una configurazione dell'elemento 'clipPath' al costruttore.

```csharp
public static TBuilder AddClipPath<TBuilder>(this TBuilder builder, 
    Action<SVGClipPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'clipPath'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGClipPathElementBuilder](../../svgclippathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
