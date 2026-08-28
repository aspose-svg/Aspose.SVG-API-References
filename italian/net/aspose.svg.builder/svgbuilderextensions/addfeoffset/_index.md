---
title: "SVGBuilderExtensions.AddFeOffset"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddFeOffset. Aggiunge una configurazione dell'elemento feOffset al builder. Questo elemento sposta l'immagine di input di un vettore specificato."
type: docs
weight: 260
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfeoffset/
---
## AddFeOffset<TBuilder>(*this TBuilder, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset}

Aggiunge una configurazione dell'elemento 'feOffset' al builder. Questo elemento sposta l'immagine di input di un vettore specificato.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, 
    Action<SVGFEOffsetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'feOffset'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeOffset<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset_1}

Aggiunge un elemento 'feOffset' al builder SVG, creando un effetto di offset spostando l'immagine di input di un vettore specificato.

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEOffsetElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'feOffset'. |
| dx | La distanza di offset orizzontale. Parametro opzionale. |
| dy | La distanza di offset verticale. Parametro opzionale. |
| in | L'immagine di input a cui verrà applicato l'offset. Può essere una stringa o un FilterInput. Parametro opzionale. |
| result | L'identificatore di risultato per questo filtro primitivo. Parametro opzionale. |
| x | La coordinata x della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| y | La coordinata y della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| width | La larghezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| altezza | L'altezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| riempimento | Il colore di riempimento, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| tratto | Il colore del tratto, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento filtro primitivo. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente lo SVGFEOffsetElementBuilder. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
