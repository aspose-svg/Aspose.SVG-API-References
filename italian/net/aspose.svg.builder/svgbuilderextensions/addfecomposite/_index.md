---
title: "SVGBuilderExtensions.AddFeComposite"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddFeComposite di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento feComposite al builder. Questo elemento esegue una combinazione bitwise di due grafiche di input"
type: docs
weight: 160
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfecomposite/
---
## AddFeComposite<TBuilder>(*this TBuilder, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite}

Aggiunge una configurazione dell'elemento 'feComposite' al costruttore. Questo elemento esegue una combinazione bitwise di due grafici di input.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    Action<SVGFECompositeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'feComposite'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComposite<TBuilder>(*this TBuilder, CompositeOperator?, double?, double?, double?, double?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFECompositeElementBuilder&gt;*) {#addfecomposite_1}

Aggiunge un elemento 'feComposite' al costruttore SVG, specificando l'operazione composita e varie altre proprietà per combinare le immagini di input.

```csharp
public static TBuilder AddFeComposite<TBuilder>(this TBuilder builder, 
    CompositeOperator? compositeOperator, double? k1, double? k2, double? k3, double? k4, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFECompositeElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'feComposite'. |
| compositeOperator | L'operatore composite da utilizzare. Parametro opzionale. |
| k1 | Il primo valore numerico per l'operazione composita. Parametro opzionale. |
| k2 | Il secondo valore numerico per l'operazione composita. Parametro opzionale. |
| k3 | Il terzo valore numerico per l'operazione composita. Parametro opzionale. |
| k4 | Il quarto valore numerico per l'operazione composita. Parametro opzionale. |
| in | Il primo input per l'effetto composito. Può essere una stringa o un FilterInput. Parametro opzionale. |
| in2 | Il secondo input per l'effetto composito. Può essere una stringa o un FilterInput. Parametro opzionale. |
| result | L'identificatore di risultato per questo filtro primitivo. Parametro opzionale. |
| x | La coordinata x della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| y | La coordinata y della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| width | La larghezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| altezza | L'altezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| riempimento | Il colore di riempimento, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| tratto | Il colore del tratto, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento filtro primitivo. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente lo SVGFECompositeElementBuilder. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* enum [CompositeOperator](../../compositeoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFECompositeElementBuilder](../../svgfecompositeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
