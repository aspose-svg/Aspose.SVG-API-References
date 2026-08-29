---
title: "SVGBuilderExtensions.AddStop"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddStop-methode. Voegt een stop‑elementconfiguratie toe aan de builder voor het definiëren van kleurverloop‑stops."
type: docs
weight: 480
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

Voegt een 'stop' elementconfiguratie toe aan de builder voor het definiëren van kleurverloopstops.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'stop'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

Voegt een 'stop' element toe aan het kleurverloop in de SVG builder, waarbij kleur en doorzichtigheid op een specifieke offset worden gespecificeerd.

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'stop'-element zal worden toegevoegd. |
| stopColor | De kleur bij de stop. Optionele parameter. |
| stopOpacity | De opacity bij de stop. Optionele parameter. |
| offset | De offset van de stop binnen het kleurverloop. Kan een double of een ValueTuple met StopUnitType zijn. Optionele parameter. |
| id | De unieke identifier voor het stop‑element. Optionele parameter. |
| extend | Een optionele actie om de stop-elementbouwer verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
