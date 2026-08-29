---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions RepeatDur-methode. Stelt het repeatDur‑attribuut in dat de totale duur specificeert waarvoor de animatie moet herhalen."
type: docs
weight: 1960
url: /nl/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

Stelt het 'repeatDur' attribuut in, waarbij de totale duur wordt gespecificeerd waarvoor de animatie moet herhalen.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| duur | De totale duur voor het herhalen van de animatie. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

Stelt het 'repeatDur' attribuut in, waarbij een onbepaalde totale duur voor de animatie wordt gespecificeerd met behulp van een vooraf gedefinieerde enum.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De vooraf gedefinieerde onbepaalde totale duur voor het herhalen van de animatie. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
