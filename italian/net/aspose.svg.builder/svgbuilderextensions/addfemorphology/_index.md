---
title: "SVGBuilderExtensions.AddFeMorphology"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddFeMorphology. Aggiunge una configurazione dell'elemento feMorphology al builder. Questo elemento è usato per applicare operazioni morfologiche come dilatazione o erosione sull'immagine di input"
type: docs
weight: 250
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfemorphology/
---
## AddFeMorphology<TBuilder>(*this TBuilder, Action&lt;SVGFEMorphologyElementBuilder&gt;*) {#addfemorphology}

Aggiunge una configurazione dell'elemento 'feMorphology' al builder. Questo elemento è usato per applicare operazioni morfologiche come dilatazione o erosione sull'immagine di input.

```csharp
public static TBuilder AddFeMorphology<TBuilder>(this TBuilder builder, 
    Action<SVGFEMorphologyElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'feMorphology'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFEMorphologyElementBuilder](../../svgfemorphologyelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeMorphology<TBuilder>(*this TBuilder, MorphologyOperator?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEMorphologyElementBuilder&gt;*) {#addfemorphology_1}

Aggiunge un elemento 'feMorphology' al builder SVG, applicando un'operazione morfologica all'immagine di input.

```csharp
public static TBuilder AddFeMorphology<TBuilder>(this TBuilder builder, 
    MorphologyOperator? @operator = default, OneOf<double, (double, double)> radius = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEMorphologyElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'feMorphology'. |
| operatore | L'operatore morfologico da applicare. Parametro opzionale. |
| raggio | Il raggio per l'operazione morfologica. Può essere un double o un ValueTuple di due double. Parametro opzionale. |
| in | L'immagine di input a cui verrà applicata l'operazione morfologica. Può essere una stringa o un FilterInput. Parametro opzionale. |
| result | L'identificatore di risultato per questo filtro primitivo. Parametro opzionale. |
| x | La coordinata x della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| y | La coordinata y della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| width | La larghezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| altezza | L'altezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| riempimento | Il colore di riempimento, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| tratto | Il colore del tratto, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento filtro primitivo. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il SVGFEMorphologyElementBuilder. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* enum [MorphologyOperator](../../morphologyoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEMorphologyElementBuilder](../../svgfemorphologyelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
