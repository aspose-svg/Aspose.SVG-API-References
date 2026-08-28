---
title: "SVGBuilderExtensions.OnPause"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnPause. Imposta l'attributo dell'evento onpause per gestire gli eventi di pausa, tipicamente per gli elementi multimediali."
type: docs
weight: 1650
url: /it/net/aspose.svg.builder/svgbuilderextensions/onpause/
---
## SVGBuilderExtensions.OnPause<TBuilder> method

Imposta l'attributo evento 'onpause' per gestire gli eventi di pausa, tipicamente per gli elementi multimediali.

```csharp
public static TBuilder OnPause<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione o lo script JavaScript da eseguire quando il media è in pausa. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
