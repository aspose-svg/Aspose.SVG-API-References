---
title: "ICSSCharsetRule 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule 接口。CSSCharsetRule 接口表示 CSS 样式表中的字符集规则。encoding 属性的值不影响 DOM 对象中文本数据的编码，该编码始终为 UTF-16。样式表加载后，encoding 属性的值为字符集规则中找到的值。如果原始文档中没有字符集，则不会创建 CSSCharsetRule。encoding 属性的值也可用作序列化样式表时所使用编码的提示。"
type: docs
weight: 2530
url: /zh/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule 接口表示 CSS 样式表中的 @charset 规则。encoding 属性的值不影响 DOM 对象中文本数据的编码；该编码始终为 UTF-16。样式表加载后，encoding 属性的值即为 @charset 规则中找到的值。如果原始文档中没有 @charset，则不会创建 CSSCharsetRule。encoding 属性的值也可以作为序列化样式表时使用的编码的提示。

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | 此 @charset 规则使用的编码信息。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
