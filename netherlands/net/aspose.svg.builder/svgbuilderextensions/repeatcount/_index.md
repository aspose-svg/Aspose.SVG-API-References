---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions RepeatCount-methode. Stelt het repeatCount-attribuut in dat bepaalt hoe vaak de animatie moet herhalen"
type: docs
weight: 1950
url: /nl/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

Stelt het 'repeatCount' attribuut in, waarbij wordt gedefinieerd hoe vaak de animatie moet herhalen.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | Het aantal keren dat de animatie moet herhalen. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

Stelt het 'repeatCount' attribuut in, waarbij een onbepaalde herhalingswaarde voor de animatie wordt gedefinieerd met behulp van een vooraf gedefinieerde enum.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De vooraf gedefinieerde oneindige herhalingswaarde voor de animatie. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
