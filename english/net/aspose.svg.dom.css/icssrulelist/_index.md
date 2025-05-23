---
title: ICSSRuleList Interface
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Dom.Css.ICSSRuleList interface. The CSSRuleList interface provides the abstraction of an ordered collection of CSS rules
type: docs
weight: 2630
url: /net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

The CSSRuleList interface provides the abstraction of an ordered collection of CSS rules.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | Used to retrieve a CSS rule by method item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). The order in this collection represents the order of the rules in the CSS style sheet. If index is greater than or equal to the number of rules in the list, this returns null. |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | The number of CSSRules in the list. The range of valid child rule indices is 0 to length-1 inclusive. |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
