---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddBuilder-Methode. Fügt einen vorhandenen SVG-Element‑Builder zum aktuellen SVG-Element‑Builder hinzu. Diese Methode wird verwendet, um einen vordefinierten SVG-Element‑Builder in den aktuellen Builder einzubeziehen."
type: docs
weight: 60
url: /de/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Fügt einen bestehenden SVG‑Element‑Builder zum aktuellen SVG‑Element‑Builder hinzu. Diese Methode wird verwendet, um einen vordefinierten SVG‑Element‑Builder in den aktuellen Builder zu integrieren.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| TElementBuilder | Der Typ des zu konfigurierenden SVG-Element‑Builders. TElementBuilder muss ISVGElementBuilder implementieren. |
| builder | Der SVG-Element‑Builder, zu dem der andere Element‑Builder hinzugefügt wird. |
| elementBuilder | Der hinzuzufügende SVG-Element‑Builder. |

### Rückgabewert

Der ursprüngliche SVG-Element-Builder für Methodenverkettung.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
