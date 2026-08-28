---
title: "SVGBuilderExtensions.OnCut"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnCut. Imposta l'attributo dell'evento oncut definendo uno script da eseguire quando il contenuto viene tagliato dall'elemento SVG"
type: docs
weight: 1290
url: /it/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

Imposta l'attributo evento 'oncut', definendo uno script da eseguire quando il contenuto viene tagliato dall'elemento SVG.

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire sull'evento di taglio. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
