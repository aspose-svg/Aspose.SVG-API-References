---
title: "SVGBuilderExtensions.Filter"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Filter di SVGBuilderExtensions. Imposta l'attributo filter per un elemento SVG usando una configurazione personalizzata"
type: docs
weight: 840
url: /it/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

Imposta l'attributo 'filter' per un elemento SVG utilizzando una configurazione personalizzata.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | Un delegato per configurare il FilterValueListBuilder. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
