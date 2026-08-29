---
title: "ICSSRuleList‑interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSRuleList‑interface. De CSSRuleList‑interface biedt de abstractie van een geordende collectie CSS‑regels."
type: docs
weight: 2630
url: /nl/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

De CSSRuleList interface biedt de abstractie van een geordende collectie van CSS‑regels.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | Wordt gebruikt om een CSS‑regel op te halen via de methode item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). De volgorde in deze collectie vertegenwoordigt de volgorde van de regels in het CSS‑stijlblad. Als index groter dan of gelijk aan het aantal regels in de lijst is, retourneert dit null. |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | Het aantal CSSRules in de lijst. Het bereik van geldige kind‑regel‑indices is 0 tot en met length‑1. |

### Zie ook

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
