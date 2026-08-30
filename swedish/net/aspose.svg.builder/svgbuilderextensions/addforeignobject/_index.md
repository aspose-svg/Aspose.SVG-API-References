---
title: "SVGBuilderExtensions.AddForeignObject"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddForeignObject-metoden. Lägger till en foreignObject-elementkonfiguration till byggaren."
type: docs
weight: 310
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addforeignobject/
---
## SVGBuilderExtensions.AddForeignObject<TBuilder> method

Lägger till en 'foreignObject'-elementkonfiguration till byggaren.

```csharp
public static TBuilder AddForeignObject<TBuilder>(this TBuilder builder, 
    Action<SVGForeignObjectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för elementet 'foreignObject'. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGForeignObjectElementBuilder](../../svgforeignobjectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
