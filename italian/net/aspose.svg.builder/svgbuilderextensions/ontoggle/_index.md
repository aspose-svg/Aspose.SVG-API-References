---
title: "SVGBuilderExtensions.OnToggle"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo OnToggle di SVGBuilderExtensions. Imposta l'attributo evento ontoggle per gestire gli eventi quando l'utente attiva/disattiva un controllo come un elemento details"
type: docs
weight: 1820
url: /it/net/aspose.svg.builder/svgbuilderextensions/ontoggle/
---
## SVGBuilderExtensions.OnToggle<TBuilder> method

Imposta l'attributo evento 'ontoggle' per gestire gli eventi quando l'utente attiva o disattiva un controllo, come un elemento `details`.

```csharp
public static TBuilder OnToggle<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire quando un controllo viene attivato/disattivato. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
