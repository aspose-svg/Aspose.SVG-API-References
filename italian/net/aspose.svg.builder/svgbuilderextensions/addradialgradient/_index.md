---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddRadialGradient. Aggiunge una configurazione dell'elemento radialGradient al builder."
type: docs
weight: 440
url: /it/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Aggiunge una configurazione dell'elemento 'radialGradient' al costruttore.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'radialGradient'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Aggiunge un elemento 'radialGradient' al costruttore SVG, specificando il suo centro, raggio e punti focali, insieme ad altre proprietà del gradiente.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'radialGradient'. |
| cx | La coordinata x del centro del gradiente. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| cy | La coordinata y del centro del gradiente. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| r | Il raggio del gradiente. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| fx | La coordinata x del punto focale del gradiente. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| fy | La coordinata y del punto focale del gradiente. Può essere un double o un ValueTuple con LengthType. Parametro opzionale. |
| gradientUnits | Specifica il sistema di coordinate per il gradiente. Parametro opzionale. |
| spreadMethod | Definisce come il gradiente si estende oltre i suoi punti di inizio e fine. Parametro opzionale. |
| href | Il riferimento a un altro gradiente, se applicabile. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento gradiente. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il costruttore dell'elemento gradiente radiale. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
