---
title: "SVGBuilderExtensions.AddSymbol"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddSymbol‑Methode. Fügt dem Builder eine Symbol‑Elementkonfiguration hinzu."
type: docs
weight: 520
url: /de/net/aspose.svg.builder/svgbuilderextensions/addsymbol/
---
## SVGBuilderExtensions.AddSymbol<TBuilder> method

Fügt dem Builder eine Konfiguration für das 'symbol'-Element hinzu.

```csharp
public static TBuilder AddSymbol<TBuilder>(this TBuilder builder, 
    Action<SVGSymbolElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'symbol'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGSymbolElementBuilder](../../svgsymbolelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
