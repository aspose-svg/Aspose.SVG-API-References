---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions KeySplines-Methode. Setzt das keySplines-Attribut, das die Kontrollpunkte für die Taktung der Animation angibt."
type: docs
weight: 1060
url: /de/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

Setzt das Attribut 'keySplines' und gibt die Kontrollpunkte für die Ablaufgeschwindigkeit der Animation an.

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| buildSplines | Die Aktion zum Erstellen der Spline-Konfiguration. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
