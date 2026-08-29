---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddLinearGradient methode. Voegt een linearGradient-elementconfiguratie toe aan de builder"
type: docs
weight: 360
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Voegt een 'linearGradient'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'linearGradient'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Voegt een 'linearGradient'-element toe aan de SVG-builder, waarbij de start- en eindposities worden gespecificeerd, samen met andere verloop‑eigenschappen.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'linearGradient'-element zal worden toegevoegd. |
| x1 | De start‑x‑coördinaat voor de gradient. Kan een double of een ValueTuple met LengthType zijn. |
| y1 | De start‑y‑coördinaat voor de gradient. Kan een double of een ValueTuple met LengthType zijn. |
| x2 | De eind‑x‑coördinaat voor de gradient. Kan een double of een ValueTuple met LengthType zijn. |
| y2 | De eind‑y‑coördinaat voor de gradient. Kan een double of een ValueTuple met LengthType zijn. |
| gradientUnits | Specificeert het coördinatensysteem voor de gradiënt. Optionele parameter. |
| spreadMethod | Definieert hoe de gradiënt zich verspreidt buiten de start- en eindpunten. Optionele parameter. |
| href | De verwijzing naar een andere gradiënt, indien van toepassing. Optionele parameter. |
| id | De unieke identifier voor het gradiëntelement. Optionele parameter. |
| extend | Een optionele actie om de linear gradient-elementbuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
