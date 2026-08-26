---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddDefs-Methode. Fügt dem Builder eine Konfiguration für ein defs-Definitions‑Element hinzu"
type: docs
weight: 100
url: /de/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

Fügt dem Builder eine 'defs' (Definitions) Elementkonfiguration hinzu.

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'defs'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
