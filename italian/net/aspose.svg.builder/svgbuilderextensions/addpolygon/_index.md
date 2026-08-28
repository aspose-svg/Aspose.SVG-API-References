---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddPolygon. Aggiunge una configurazione dell'elemento poligono al builder."
type: docs
weight: 420
url: /it/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Aggiunge una configurazione dell'elemento 'polygon' al costruttore.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'polygon'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Aggiunge un elemento 'polygon' al costruttore SVG, specificando i suoi vertici e gli stili.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'polygon'. |
| points | Un array di double che rappresenta i punti del poligono (coordinate x e y alternate). |
| riempimento | Il colore di riempimento o lo stile di pittura per il poligono. Può essere un valore di enum Color o Paint o un ID del server di pittura. Parametro opzionale. |
| tratto | Il colore del tratto o lo stile di pittura per il poligono. Può essere un valore di enum Color o Paint o un ID del server di pittura. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento poligono. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il costruttore dell'elemento poligono. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
