---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddLinearGradient di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento linearGradient al builder"
type: docs
weight: 360
url: /it/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Aggiunge una configurazione dell'elemento 'linearGradient' al costruttore.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'linearGradient'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Aggiunge un elemento 'linearGradient' al costruttore SVG, specificando le sue posizioni di inizio e fine, insieme ad altre proprietà del gradiente.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'linearGradient'. |
| x1 | La coordinata x iniziale per il gradiente. Può essere un double o un ValueTuple con LengthType. |
| y1 | La coordinata y iniziale per il gradiente. Può essere un double o un ValueTuple con LengthType. |
| x2 | La coordinata x finale per il gradiente. Può essere un double o un ValueTuple con LengthType. |
| y2 | La coordinata y finale per il gradiente. Può essere un double o un ValueTuple con LengthType. |
| gradientUnits | Specifica il sistema di coordinate per il gradiente. Parametro opzionale. |
| spreadMethod | Definisce come il gradiente si estende oltre i suoi punti di inizio e fine. Parametro opzionale. |
| href | Il riferimento a un altro gradiente, se applicabile. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento gradiente. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il builder dell'elemento linear gradient. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
