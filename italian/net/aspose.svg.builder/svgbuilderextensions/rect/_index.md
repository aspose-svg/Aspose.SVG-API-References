---
title: "SVGBuilderExtensions.Rect"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions Rect. Imposta gli attributi x, y, width e height per un elemento SVG per definire un rettangolo."
type: docs
weight: 1920
url: /it/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

Imposta gli attributi 'x', 'y', 'width' e 'height' per un elemento SVG per definire un rettangolo.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| x | La coordinata x del rettangolo. |
| y | La coordinata y del rettangolo. |
| width | La larghezza del rettangolo. |
| altezza | L'altezza del rettangolo. |
| tipo | Il tipo di unità di lunghezza per tutte le dimensioni (il valore predefinito è pixel). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
