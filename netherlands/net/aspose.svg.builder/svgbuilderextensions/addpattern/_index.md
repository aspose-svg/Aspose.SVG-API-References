---
title: "SVGBuilderExtensions.AddPattern"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddPattern-methode. Voegt een patroon‑elementconfiguratie toe aan de builder"
type: docs
weight: 410
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

Voegt een 'pattern'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'pattern'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

Voegt een 'pattern'-element toe aan de SVG-builder, waarbij het coördinatensysteem en de eenheden voor de inhoud van het patroon worden gespecificeerd.

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'pattern'-element zal worden toegevoegd. |
| patternUnits | Specificeert het coördinatensysteem voor het patroon. Optionele parameter. |
| patternContentUnits | Specificeert het coördinatensysteem voor de inhoud binnen het patroon. Optionele parameter. |
| href | De verwijzing naar een ander patroon, indien van toepassing. Optionele parameter. |
| id | De unieke identifier voor het patroon‑element. Optionele parameter. |
| extend | Een optionele actie om de patroon‑element‑builder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
