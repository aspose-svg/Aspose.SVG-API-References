---
title: "ICSSImportRule 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSImportRule 接口。CSSImportRule 接口表示 CSS 样式表中的导入规则。该导入规则用于从其他样式表导入样式规则。"
type: docs
weight: 2560
url: /zh/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule 接口表示 CSS 样式表中的 @import 规则。@import 规则用于从其他样式表导入样式规则。

```csharp
public interface ICSSImportRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | 要导入的样式表的位置。该属性不会在 URI 周围包含 "url(...)" 说明符。 |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | 此样式表可能使用的媒体类型列表。 |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | 此规则引用的样式表（如果已加载）。如果样式表尚未加载或将不会加载（例如，样式表针对用户代理不支持的媒体类型），则此属性的值为 null。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
