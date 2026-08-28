---
title: "SVGBuilderExtensions.Mask"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Mask. Imposta l'attributo mask per un elemento SVG usando una configurazione mask personalizzata"
type: docs
weight: 1150
url: /it/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Imposta l'attributo 'mask' per un elemento SVG utilizzando una configurazione di maschera personalizzata.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Un delegato per configurare la maschera. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
