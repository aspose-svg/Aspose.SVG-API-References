---
title: "SVGBuilderExtensions.AddText"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddText di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento testo al builder."
type: docs
weight: 530
url: /it/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Aggiunge una configurazione dell'elemento 'text' al costruttore.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'text'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Aggiunge un elemento 'text' con contenuto e attributi specificati al costruttore SVG.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, che consente il chaining. |
| costruttore | L'istanza del builder a cui verrà aggiunto l'elemento 'text'. |
| content | Il contenuto testuale da visualizzare all'interno dell'elemento 'text'. |
| x | La coordinata x per l'elemento testo. Può essere un valore double o una tupla di double e LengthType. |
| y | La coordinata y per l'elemento testo. Può essere un valore double o una tupla di double e LengthType. |
| fontSize | La dimensione del font per il testo. Può essere un valore double o una tupla di double e LengthType. |
| fontStyle | Lo stile del font per il testo (ad es., normal, italic, oblique). |
| fontFamily | La famiglia del font per il testo (ad es., Arial, Verdana). |
| fontWeight | Il peso (spessore) del font (ad es., normal, bold). |
| riempimento | Il colore di riempimento o lo stile di pittura per il testo. Può essere un Color o un valore enum Paint o un ID del server di pittura. |
| tratto | Il colore del tratto o lo stile di pittura per il testo. Può essere un Color o un valore enum Paint o un ID del server di pittura. |
| id | L'identificatore univoco per l'elemento di testo. |
| estendi | Un'azione opzionale per configurare ulteriormente il costruttore dell'elemento di testo. |

### Valore di ritorno

L'istanza del costruttore per concatenare ulteriori aggiunte o configurazioni.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
