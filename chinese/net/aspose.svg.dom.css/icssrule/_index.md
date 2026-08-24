---
title: "ICSSRule 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.ICSSRule 接口。CSSRule 接口是任何类型 CSS 声明的抽象基础接口。它包括规则集和 at-rule。实现应保留 CSS 样式表中指定的所有规则，即使解析器未识别某些规则。未识别的规则使用 ICSSUnknownRule 接口表示。"
type: docs
weight: 2620
url: /zh/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

CSSRule 接口是任何类型 CSS 声明的抽象基接口。它包括规则集和 at-rule。实现应保留 CSS 样式表中指定的所有规则，即使解析器未识别该规则。未识别的规则使用 ICSSUnknownRule 接口表示。

```csharp
public interface ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | 规则的可解析文本表示。这反映了规则的当前状态，而不是其初始值。 |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | 如果此规则包含在另一个规则内部（例如位于 @media 块中的样式规则），则它是包含该规则的规则。如果此规则未嵌套在任何其他规则中，则返回 null。 |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | 包含此规则的样式表。 |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | 规则的类型，如上所定义。期望可以使用特定绑定的强制转换方法，将 CSSRule 接口的实例向下转换为该类型所暗示的具体派生接口。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
