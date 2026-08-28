---
title: "SVGBuilderExtensions.OnStalled"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnStalled di SVGBuilderExtensions. Imposta l'attributo evento onstalled per gestire gli eventi quando il trasferimento dei dati multimediali si interrompe in modo imprevisto"
type: docs
weight: 1780
url: /it/net/aspose.svg.builder/svgbuilderextensions/onstalled/
---
## SVGBuilderExtensions.OnStalled<TBuilder> method

Imposta l'attributo evento 'onstalled' per gestire gli eventi quando il trasferimento dei dati multimediali è interrotto inaspettatamente.

```csharp
public static TBuilder OnStalled<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione o script JavaScript da eseguire quando il trasferimento dei dati multimediali si blocca. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
