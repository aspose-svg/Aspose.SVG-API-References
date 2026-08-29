---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddImage-methode. Voegt een afbeeldingselementconfiguratie toe aan de bouwer."
type: docs
weight: 330
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Voegt een 'image'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie-actie voor het 'image'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

Voegt een 'image'-element toe aan de SVG-builder, waarmee een externe afbeelding in het SVG-document wordt ingesloten.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-bouwerinstantie waaraan het 'image'-element zal worden toegevoegd. |
| href | De URL of referentie naar de externe afbeelding. Optionele parameter. |
| x | De x-coördinaat waar de afbeelding wordt geplaatst. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y-coördinaat waar de afbeelding wordt geplaatst. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van de afbeelding. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van de afbeelding. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| id | De unieke identifier voor het afbeeldingselement. Optionele parameter. |
| extend | Een optionele actie om de SVGImageElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
