---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo AddEllipse di SVGBuilderExtensions. Aggiunge una configurazione dell'elemento ellisse al builder"
type: docs
weight: 120
url: /it/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Aggiunge una configurazione dell'elemento 'ellipse' al costruttore.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'ellipse'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Aggiunge un elemento 'ellipse' al costruttore SVG, specificando il suo centro, i raggi e gli stili.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'ellipse'. |
| cx | La coordinata x del centro dell'ellisse. Può essere un valore double o una tupla di double e LengthType. |
| cy | La coordinata y del centro dell'ellisse. Può essere un valore double o una tupla di double e LengthType. |
| rx | Il raggio x dell'ellisse. Può essere un valore double o una tupla di double e LengthType. |
| ry | Il raggio y dell'ellisse. Può essere un valore double o una tupla di double e LengthType. |
| riempimento | Il colore di riempimento o lo stile di pittura per l'ellisse. Può essere un Color o un valore enum Paint o un ID del server di pittura. Parametro opzionale. |
| tratto | Il colore del tratto o lo stile di pittura per l'ellisse. Può essere un Color o un valore enum Paint o un ID del server di pittura. Parametro opzionale. |
| id | L'identificatore unico per l'elemento ellisse. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il builder dell'elemento ellisse. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
