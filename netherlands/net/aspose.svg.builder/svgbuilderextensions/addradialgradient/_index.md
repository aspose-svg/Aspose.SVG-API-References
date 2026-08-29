---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddRadialGradient-methode. Voegt een radialGradient‑elementconfiguratie toe aan de builder"
type: docs
weight: 440
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Voegt een 'radialGradient'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'radialGradient'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Voegt een 'radialGradient'-element toe aan de SVG-builder, waarbij het centrum, de radius en de brandpunten worden gespecificeerd, samen met andere verloop‑eigenschappen.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'radialGradient'-element zal worden toegevoegd. |
| cx | De x-coördinaat van het middelpunt van de gradient. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| cy | De y-coördinaat van het middelpunt van de gradient. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| r | De straal van de gradient. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fx | De x-coördinaat van het brandpunt van de gradient. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fy | De y-coördinaat van het brandpunt van de gradiënt. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| gradientUnits | Specificeert het coördinatensysteem voor de gradiënt. Optionele parameter. |
| spreadMethod | Definieert hoe de gradiënt zich verspreidt buiten de start- en eindpunten. Optionele parameter. |
| href | De verwijzing naar een andere gradiënt, indien van toepassing. Optionele parameter. |
| id | De unieke identifier voor het gradiëntelement. Optionele parameter. |
| extend | Een optionele actie om de radiale gradiëntelementbouwer verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
