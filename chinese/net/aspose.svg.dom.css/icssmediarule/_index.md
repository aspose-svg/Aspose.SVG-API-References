---
title: "ICSSMediaRule 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSMediaRule 接口。CSSMediaRule 接口表示 CSS 样式表中的媒体规则。媒体规则可用于限定特定媒体类型的样式规则"
type: docs
weight: 2600
url: /zh/net/aspose.svg.dom.css/icssmediarule/
---
## ICSSMediaRule interface

CSSMediaRule 接口表示 CSS 样式表中的 @media 规则。@media 规则可用于限定特定媒体类型的样式规则。

```csharp
public interface ICSSMediaRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssmediarule/cssrules/) { get; } | 媒体块中包含的所有 CSS 规则的列表。 |
| [Media](../../aspose.svg.dom.css/icssmediarule/media/) { get; } | 此规则的媒体类型列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssmediarule/deleterule/)(*long*) | 用于从媒体块中删除规则。 |
| [InsertRule](../../aspose.svg.dom.css/icssmediarule/insertrule/)(*string, long*) | 用于向媒体块中插入新规则。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
