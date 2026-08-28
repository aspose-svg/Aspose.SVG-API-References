---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo SVGBuilderExtensions SetPreserveAspectRatio. Imposta l'attributo preserveAspectRatio per un elemento SVG"
type: docs
weight: 2020
url: /it/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Imposta l'attributo 'preserveAspectRatio' per un elemento SVG.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Parametro | Descrizione |
| --- | --- |
| TBuilder | Il tipo del costruttore di elementi SVG. |
| costruttore | L'istanza del costruttore. |
| align | L'impostazione di allineamento per il rapporto d'aspetto. |
| meetOrSlice | Specifica come viene preservato il rapporto d'aspetto (il valore predefinito è 'Meet'). |

### Valore di ritorno

L'istanza del costruttore per concatenazione.

### Vedi anche

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
