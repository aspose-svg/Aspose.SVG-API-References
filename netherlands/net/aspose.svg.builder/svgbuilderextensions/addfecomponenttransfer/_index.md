---
title: "SVGBuilderExtensions.AddFeComponentTransfer"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFeComponentTransfer-methode. Voegt een feComponentTransfer-elementconfiguratie toe aan de builder. Dit element voert een componentgewijze herschikking van gegevens uit voor kleurkanalen"
type: docs
weight: 150
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfecomponenttransfer/
---
## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer}

Voegt een 'feComponentTransfer'‑elementconfiguratie toe aan de builder. Dit element voert een component‑gewijze herschikking van gegevens voor kleurkanalen uit.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEComponentTransferElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'feComponentTransfer'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeComponentTransfer<TBuilder>(*this TBuilder, Action&lt;SVGFEFuncAElementBuilder&gt;, Action&lt;SVGFEFuncRElementBuilder&gt;, Action&lt;SVGFEFuncGElementBuilder&gt;, Action&lt;SVGFEFuncBElementBuilder&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEComponentTransferElementBuilder&gt;*) {#addfecomponenttransfer_1}

Voegt een 'feComponentTransfer'‑element toe aan de SVG‑builder, waardoor een component‑gewijze herschikking van gegevens voor kleurkanalen mogelijk wordt.

```csharp
public static TBuilder AddFeComponentTransfer<TBuilder>(this TBuilder builder, 
    Action<SVGFEFuncAElementBuilder> a = null, Action<SVGFEFuncRElementBuilder> r = null, 
    Action<SVGFEFuncGElementBuilder> g = null, Action<SVGFEFuncBElementBuilder> b = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEComponentTransferElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'feComponentTransfer'-element zal worden toegevoegd. |
| a | Een actie om het 'feFuncA'-component voor het alfakanaal te configureren. Optionele parameter. |
| r | Een actie om het 'feFuncR'-component voor het rode kanaal te configureren. Optionele parameter. |
| g | Een actie om het 'feFuncG'-component voor het groene kanaal te configureren. Optionele parameter. |
| b | Een actie om het 'feFuncB'-component voor het blauwe kanaal te configureren. Optionele parameter. |
| in | De invoer voor het component‑transfer effect. Kan een string of een FilterInput zijn. Optionele parameter. |
| result | De resultaat‑identifier voor dit filter‑primitive. Optionele parameter. |
| x | De x-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fill | De vulkleur, verf of paint server-id voor het element. Optionele parameter. |
| stroke | De lijnkleur, verf of paint server-id voor het element. Optionele parameter. |
| id | De unieke identifier voor het filterprimitive element. Optionele parameter. |
| extend | Een optionele actie om de SVGFEComponentTransferElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [SVGFEFuncAElementBuilder](../../svgfefuncaelementbuilder/)
* class [SVGFEFuncRElementBuilder](../../svgfefuncrelementbuilder/)
* class [SVGFEFuncGElementBuilder](../../svgfefuncgelementbuilder/)
* class [SVGFEFuncBElementBuilder](../../svgfefuncbelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEComponentTransferElementBuilder](../../svgfecomponenttransferelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
