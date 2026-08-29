---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions OnFocusIn‑methode. Stelt het onfocusin‑gebeurtenisattribuut in voor het afhandelen van focus‑in‑gebeurtenissen op het element."
type: docs
weight: 1450
url: /nl/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Stelt het 'onfocusin' gebeurtenisattribuut in voor het afhandelen van focus-in-gebeurtenissen op het element.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De JavaScript‑functie of het script dat moet worden uitgevoerd wanneer het element focus krijgt, meestal vóór het 'onfocus'-gebeurtenis. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Het 'onfocusin'-gebeurtenis wordt geactiveerd wanneer een element op het punt staat focus te krijgen. Dit gebeurtenis verschilt van 'onfocus' doordat het bubbling ondersteunt en ook kan worden gebruikt om focuswijzigingen op kindelementen te detecteren.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
