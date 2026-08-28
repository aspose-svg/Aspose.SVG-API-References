---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions OnCopy. Imposta l'attributo oncopy definendo uno script da eseguire quando il contenuto viene copiato dall'elemento SVG"
type: docs
weight: 1270
url: /it/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

Imposta l'attributo evento 'oncopy', definendo uno script da eseguire quando il contenuto viene copiato dall'elemento SVG.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore di elementi SVG. |
| value | La funzione JavaScript o lo script da eseguire sull'evento di copia. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
