---
title: "SVGBuilderExtensions.ClipPath"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions ClipPath. Imposta l'attributo clip-path per un elemento SVG"
type: docs
weight: 650
url: /it/net/aspose.svg.builder/svgbuilderextensions/clippath/
---
## SVGBuilderExtensions.ClipPath<TBuilder> method

Imposta l'attributo 'clip-path' per un elemento SVG.

```csharp
public static TBuilder ClipPath<TBuilder>(this TBuilder builder, Action<ClipPathBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Un delegato per configurare il percorso di ritaglio. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [ClipPathBuilder](../../clippathbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
