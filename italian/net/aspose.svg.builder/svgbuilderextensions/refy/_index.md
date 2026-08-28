---
title: "SVGBuilderExtensions.RefY"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo RefY di SVGBuilderExtensions. Imposta l'attributo refY per un elemento SVG."
type: docs
weight: 1940
url: /it/net/aspose.svg.builder/svgbuilderextensions/refy/
---
## RefY<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refy_1}

Imposta l'attributo 'refY' per un elemento SVG.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | La coordinata Y di riferimento. |
| tipo | Il tipo di unità di lunghezza (il valore predefinito è pixel). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefY<TBuilder>(*this TBuilder, [VerticalPosition](../../verticalposition/)*) {#refy}

Imposta l'attributo 'refY' per un elemento SVG usando una posizione verticale predefinita.

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, VerticalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| value | La posizione verticale predefinita. |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [VerticalPosition](../../verticalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
