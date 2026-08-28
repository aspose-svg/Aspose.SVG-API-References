---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddBuilder. Aggiunge un builder di elementi SVG esistente al builder di elementi SVG corrente. Questo metodo è usato per includere un builder di elementi SVG predefinito nel builder corrente"
type: docs
weight: 60
url: /it/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Aggiunge un costruttore di elementi SVG esistente al costruttore di elementi SVG corrente. Questo metodo è usato per includere un costruttore di elementi SVG predefinito nel costruttore corrente.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| TElementBuilder | Il tipo di builder di elementi SVG da configurare. TElementBuilder deve implementare ISVGElementBuilder. |
| costruttore | Il builder di elementi SVG al quale viene aggiunto l'altro builder di elementi. |
| elementBuilder | Il builder di elementi SVG da aggiungere. |

### Valore di ritorno

Il costruttore originale dell'elemento SVG per il chaining dei metodi.

### Vedi anche

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
