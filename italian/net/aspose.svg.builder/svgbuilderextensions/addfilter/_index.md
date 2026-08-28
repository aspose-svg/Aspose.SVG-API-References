---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddFilter di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento filtro al builder."
type: docs
weight: 300
url: /it/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Aggiunge una configurazione dell'elemento 'filter' al builder.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'filter'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Aggiunge un elemento 'filter' al builder SVG, definendo un effetto di filtro che può essere applicato agli elementi SVG.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'filter'. |
| filterUnits | Specifica il sistema di coordinate per gli attributi x, y, width e height del filtro. Parametro opzionale. |
| primitiveUnits | Specifica il sistema di coordinate per gli attributi degli elementi figlio del filtro. Parametro opzionale. |
| x | La coordinata x della regione del filtro. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| y | La coordinata y della regione del filtro. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| width | La larghezza della regione del filtro. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| altezza | L'altezza della regione del filtro. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| riempimento | Il colore di riempimento o la vernice per l'elemento filtro. Parametro opzionale. |
| tratto | Il colore del tratto o la vernice per l'elemento filtro. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento filtro. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente lo SVGFilterElementBuilder. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
