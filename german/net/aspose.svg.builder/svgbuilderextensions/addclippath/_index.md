---
title: "SVGBuilderExtensions.AddClipPath"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddClipPath Methode. Fügt dem Builder eine clipPath-Elementkonfiguration hinzu."
type: docs
weight: 80
url: /de/net/aspose.svg.builder/svgbuilderextensions/addclippath/
---
## SVGBuilderExtensions.AddClipPath<TBuilder> method

Fügt dem Builder eine 'clipPath'‑Elementkonfiguration hinzu.

```csharp
public static TBuilder AddClipPath<TBuilder>(this TBuilder builder, 
    Action<SVGClipPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Die Konfigurationsaktion für das 'clipPath'-Element. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [SVGClipPathElementBuilder](../../svgclippathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
