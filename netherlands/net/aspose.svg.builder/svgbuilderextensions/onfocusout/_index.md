---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions OnFocusOut-methode. Stelt het onfocusout‑eventattribuut in voor het afhandelen van focus‑out‑gebeurtenissen op het element."
type: docs
weight: 1460
url: /nl/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Stelt het 'onfocusout' gebeurtenisattribuut in voor het afhandelen van focus-out-gebeurtenissen op het element.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De JavaScript-functie of -script die moet worden uitgevoerd wanneer het element de focus verliest, meestal vóór het 'onblur'-event. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Het 'onfocusout'-event wordt geactiveerd wanneer een element op het punt staat de focus te verliezen. Net als 'onfocusin' ondersteunt dit event bubbling en kan het ook worden gebruikt om focuswijzigingen op kindelementen te detecteren.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
