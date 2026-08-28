---
title: "SVGBuilderExtensions.AddFeGaussianBlur"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddFeGaussianBlur. Aggiunge una configurazione dell'elemento feGaussianBlur al builder. Questo elemento applica una sfocatura gaussiana all'immagine di input"
type: docs
weight: 220
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfegaussianblur/
---
## AddFeGaussianBlur<TBuilder>(*this TBuilder, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur_1}

Aggiunge una configurazione dell'elemento 'feGaussianBlur' al builder. Questo elemento applica una sfocatura gaussiana all'immagine di input.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    Action<SVGFEGaussianBlurElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'feGaussianBlur'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeGaussianBlur<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur}

Aggiunge un elemento 'feGaussianBlur' al builder SVG, applicando un effetto di sfocatura gaussiana all'immagine di input.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> stdDeviation = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEGaussianBlurElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'feGaussianBlur'. |
| stdDeviation | La deviazione standard per l'operazione di sfocatura. Può essere un double o un ValueTuple di due double. Parametro opzionale. |
| in | L'immagine di input a cui verrà applicata la sfocatura gaussiana. Può essere una stringa o un FilterInput. Parametro opzionale. |
| result | L'identificatore di risultato per questo filtro primitivo. Parametro opzionale. |
| x | La coordinata x della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| y | La coordinata y della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| width | La larghezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| altezza | L'altezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| riempimento | Il colore di riempimento, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| tratto | Il colore del tratto, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento filtro primitivo. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente lo SVGFEGaussianBlurElementBuilder. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
