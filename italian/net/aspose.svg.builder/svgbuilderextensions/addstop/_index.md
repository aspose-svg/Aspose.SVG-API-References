---
title: "SVGBuilderExtensions.AddStop"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddStop. Aggiunge una configurazione dell'elemento stop al builder per definire le fermate del gradiente"
type: docs
weight: 480
url: /it/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

Aggiunge una configurazione dell'elemento 'stop' al costruttore per definire le fermate del gradiente.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'stop'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

Aggiunge un elemento 'stop' al gradiente nel costruttore SVG, specificando colore e opacità a un determinato offset.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'stop'. |
| stopColor | Il colore alla fermata. Parametro opzionale. |
| stopOpacity | L'opacità alla fermata. Parametro opzionale. |
| offset | L'offset della fermata all'interno del gradiente. Può essere un double o un ValueTuple con StopUnitType. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento stop. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il builder dell'elemento stop. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
