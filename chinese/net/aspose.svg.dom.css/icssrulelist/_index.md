---
title: "ICSSRuleList 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSRuleList 接口。CSSRuleList 接口提供了有序 CSS 规则集合的抽象。"
type: docs
weight: 2630
url: /zh/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList 接口提供了有序 CSS 规则集合的抽象。

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | 用于通过 method item() 检索 CSS 规则 (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList)。此集合中的顺序代表 CSS 样式表中规则的顺序。如果索引大于或等于列表中的规则数量，则返回 null。 |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | 列表中 CSSRules 的数量。有效子规则索引的范围为 0 到 length-1（含）。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
