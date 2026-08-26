---
title: "ICSSRuleList Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSRuleList Schnittstelle. Die CSSRuleList‑Schnittstelle bietet die Abstraktion einer geordneten Sammlung von CSS‑Regeln"
type: docs
weight: 2630
url: /de/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

Das CSSRuleList-Interface bietet die Abstraktion einer geordneten Sammlung von CSS-Regeln.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | Wird verwendet, um eine CSS‑Regel mit der Methode item() abzurufen (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Die Reihenfolge in dieser Sammlung entspricht der Reihenfolge der Regeln im CSS‑Stylesheet. Wenn der Index größer oder gleich der Anzahl der Regeln in der Liste ist, wird null zurückgegeben. |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | Die Anzahl der CSSRules in der Liste. Der Bereich gültiger Kindregel-Indizes ist von 0 bis Länge-1 inklusive. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
