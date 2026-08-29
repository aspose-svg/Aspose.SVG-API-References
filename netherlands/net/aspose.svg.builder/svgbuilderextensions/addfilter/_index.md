---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFilter-methode. Voegt een filter-elementconfiguratie toe aan de bouwer"
type: docs
weight: 300
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Voegt een 'filter'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie-actie voor het 'filter'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Voegt een 'filter'-element toe aan de SVG-builder, waarmee een filtereffect wordt gedefinieerd dat kan worden toegepast op SVG-elementen.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-bouwerinstantie waaraan het 'filter'-element zal worden toegevoegd. |
| filterUnits | Specificeert het coördinatensysteem voor de x-, y-, breedte- en hoogte‑attributen van het filter. Optionele parameter. |
| primitiveUnits | Specificeert het coördinatensysteem voor de attributen van de onderliggende elementen van het filter. Optionele parameter. |
| x | De x‑coördinaat van het filtergebied. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y‑coördinaat van het filtergebied. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van het filtergebied. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van het filtergebied. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fill | De vulkleur of verf voor het filterelement. Optionele parameter. |
| stroke | De lijnkleur of verf voor het filterelement. Optionele parameter. |
| id | De unieke identifier voor het filterelement. Optionele parameter. |
| extend | Een optionele actie om de SVGFilterElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
