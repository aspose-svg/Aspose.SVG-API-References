---
title: "SVGBuilderExtensions.AddFeDisplacementMap"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddFeDisplacementMap. Aggiunge una configurazione dell'elemento feDisplacementMap al builder. Questo elemento sposta un'immagine secondo una mappa vettoriale specificata"
type: docs
weight: 190
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfedisplacementmap/
---
## AddFeDisplacementMap<TBuilder>(*this TBuilder, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap}

Aggiunge una configurazione dell'elemento 'feDisplacementMap' al costruttore. Questo elemento sposta un'immagine mediante una mappa vettoriale specificata.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, 
    Action<SVGFEDisplacementMapElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'feDisplacementMap'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDisplacementMap<TBuilder>(*this TBuilder, double?, ChannelSelector?, ChannelSelector?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap_1}

Aggiunge un elemento 'feDisplacementMap' al costruttore SVG, creando un effetto che distorce un'immagine basandosi sui dati di colore di una seconda sorgente.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, double? scale = null, 
    ChannelSelector? xChannelSelector = default, ChannelSelector? yChannelSelector = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDisplacementMapElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'feDisplacementMap'. |
| scala | Il fattore di scala che determina la quantità di spostamento. Parametro opzionale. |
| xChannelSelector | Il canale dell'immagine in2 da utilizzare per lo spostamento lungo l'asse x. Parametro opzionale. |
| yChannelSelector | Il canale dell'immagine in2 da utilizzare per lo spostamento lungo l'asse y. Parametro opzionale. |
| in | L'immagine di input da spostare. Può essere una stringa o un FilterInput. Parametro opzionale. |
| in2 | L'immagine che fornisce i dati di spostamento. Può essere una stringa o un FilterInput. Parametro opzionale. |
| result | L'identificatore di risultato per questo filtro primitivo. Parametro opzionale. |
| x | La coordinata x della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| y | La coordinata y della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| width | La larghezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| altezza | L'altezza della sottozona del filtro primitivo. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| riempimento | Il colore di riempimento, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| tratto | Il colore del tratto, la vernice o l'ID del server di vernice per l'elemento. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento filtro primitivo. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente lo SVGFEDisplacementMapElementBuilder. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* enum [ChannelSelector](../../channelselector/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
