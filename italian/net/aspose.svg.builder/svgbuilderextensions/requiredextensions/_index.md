---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions RequiredExtensions. Imposta l'attributo requiredExtensions sull'elemento SVG. Questo attributo specifica quali estensioni sono necessarie affinché il frammento di documento SVG venga elaborato"
type: docs
weight: 1970
url: /it/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

Imposta l'attributo 'requiredExtensions' sull'elemento SVG. Questo attributo specifica quali estensioni sono richieste affinché il frammento di documento SVG venga elaborato.

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | Il costruttore dell'elemento SVG su cui viene impostato l'attributo. |
| value | Una stringa che rappresenta le estensioni richieste. |

### Valore di ritorno

Il costruttore originale dell'elemento SVG per il chaining dei metodi.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
