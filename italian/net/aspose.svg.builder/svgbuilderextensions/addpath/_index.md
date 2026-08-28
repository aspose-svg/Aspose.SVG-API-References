---
title: "SVGBuilderExtensions.AddPath"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions AddPath. Aggiunge una configurazione dell'elemento path al builder"
type: docs
weight: 400
url: /it/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

Aggiunge una configurazione dell'elemento 'path' al costruttore.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| configurare | L'azione di configurazione per l'elemento 'path'. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

Aggiunge un elemento 'path' al costruttore SVG, specificando i dati del percorso e gli stili.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'path'. |
| d | Un tipo OneOf che può essere una stringa che rappresenta i dati del percorso o un'azione che configura un PathBuilder. |
| riempimento | Il colore di riempimento o lo stile di pittura per il percorso. Può essere un valore Color o Paint enum o un ID del server di pittura. Parametro opzionale. |
| tratto | Il colore del tratto o lo stile di pittura per il percorso. Può essere un valore Color o Paint enum o un ID del server di pittura. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento path. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il builder dell'elemento path. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

Sovraccarico di AddPath che accetta un'azione per configurare direttamente un PathBuilder.

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del builder di elementi SVG, facilitando l'uso di un'API fluente. |
| costruttore | L'istanza del builder SVG a cui verrà aggiunto l'elemento 'path'. |
| d | Un'azione che configura un PathBuilder per definire i dati del percorso. |
| riempimento | Il colore di riempimento o lo stile di pittura per il percorso. Può essere un valore Color o Paint enum o un ID del server di pittura. Parametro opzionale. |
| tratto | Il colore del tratto o lo stile di pittura per il percorso. Può essere un valore Color o Paint enum o un ID del server di pittura. Parametro opzionale. |
| id | L'identificatore univoco per l'elemento path. Parametro opzionale. |
| estendi | Un'azione opzionale per configurare ulteriormente il builder dell'elemento path. |

### Valore di ritorno

L'istanza del builder, che consente il chaining dei metodi.

### Vedi anche

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
