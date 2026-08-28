---
title: "SVGBuilderExtensions.OnEmptied"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnEmptied. Imposta l'attributo onemptied per gestire lo svuotamento della sorgente degli elementi multimediali"
type: docs
weight: 1400
url: /it/net/aspose.svg.builder/svgbuilderextensions/onemptied/
---
## SVGBuilderExtensions.OnEmptied<TBuilder> method

Imposta l'attributo evento 'onemptied' per gestire lo svuotamento della sorgente dell'elemento media.

```csharp
public static TBuilder OnEmptied<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando la sorgente dell'elemento multimediale viene svuotata. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
