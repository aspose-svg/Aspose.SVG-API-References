---
title: "SVGBuilderExtensions.AddForeignObject"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddForeignObject-Methode. Fügt dem Builder eine Konfiguration für ein foreignObject-Element hinzu."
type: docs
weight: 310
url: /de/net/aspose.svg.builder/svgbuilderextensions/addforeignobject/
---
## SVGBuilderExtensions.AddForeignObject<TBuilder> method

Fügt dem Builder eine 'foreignObject'-Elementkonfiguration hinzu.

```csharp
public static TBuilder AddForeignObject<TBuilder>(this TBuilder builder, 
    Action<SVGForeignObjectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'foreignObject'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGForeignObjectElementBuilder](../../svgforeignobjectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
