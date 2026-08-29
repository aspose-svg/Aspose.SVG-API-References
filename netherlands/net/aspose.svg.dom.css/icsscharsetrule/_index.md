---
title: "ICSSCharsetRule Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule interface. De CSSCharsetRule interface vertegenwoordigt een charset-regel in een CSS-stijlblad. De waarde van het encoding-attribuut heeft geen invloed op de codering van tekstgegevens in de DOM-objecten; deze codering is altijd UTF-16. Nadat een stijlblad is geladen, is de waarde van het encoding-attribuut de waarde die in de charset-regel is gevonden. Als er geen charset in het oorspronkelijke document aanwezig was, wordt er geen CSSCharsetRule aangemaakt. De waarde van het encoding-attribuut kan ook worden gebruikt als hint voor de codering die wordt gebruikt bij het serialiseren van het stijlblad."
type: docs
weight: 2530
url: /nl/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

De CSSCharsetRule interface vertegenwoordigt een @charset‑regel in een CSS‑stylesheet. De waarde van het encoding‑attribuut heeft geen invloed op de codering van tekstgegevens in de DOM‑objecten; deze codering is altijd UTF-16. Nadat een stylesheet is geladen, is de waarde van het encoding‑attribuut gelijk aan de waarde die in de @charset‑regel is gevonden. Als er geen @charset in het oorspronkelijke document stond, wordt er geen CSSCharsetRule aangemaakt. De waarde van het encoding‑attribuut kan ook worden gebruikt als hint voor de codering die bij het serialiseren van de stylesheet wordt gebruikt.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | De coderingsinformatie die wordt gebruikt in deze @charset-regel. |

### Zie ook

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
