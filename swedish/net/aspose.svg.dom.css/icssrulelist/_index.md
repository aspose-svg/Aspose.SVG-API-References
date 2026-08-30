---
title: "ICSSRuleList-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSRuleList gränssnitt. CSSRuleList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS-regler."
type: docs
weight: 2630
url: /sv/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑regler.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | Används för att hämta en CSS-regel med metoden item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Ordningen i denna samling representerar ordningen av reglerna i CSS-stilmallen. Om index är större än eller lika med antalet regler i listan returneras null. |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | Antalet CSSRules i listan. Intervallet för giltiga underordnade regelindex är 0 till length-1 inklusive. |

### Se även

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
