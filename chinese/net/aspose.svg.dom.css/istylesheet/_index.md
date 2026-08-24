---
title: "IStyleSheet 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.IStyleSheet 接口。StyleSheet 接口是任何类型样式表的抽象基接口。它表示与结构化文档关联的单个样式表"
type: docs
weight: 2740
url: /zh/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet 接口是任何类型样式表的抽象基接口。它表示与结构化文档关联的单个样式表。

```csharp
public interface IStyleSheet
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | 如果样式表已应用于文档，则为 false；如果未应用，则为 true。修改此属性可能导致文档样式重新解析。只有在存在适当的媒体定义且 disabled 属性为 false 时，样式表才会生效。因此，如果媒体不适用于当前用户代理，disabled 属性将被忽略。 |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | 如果样式表是链接的样式表，则其属性值为其位置。对于内联样式表，此属性的值为 null。 |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | 样式信息的预期目标媒体。 |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | 将此样式表与文档关联的节点。对于 HTML，可能是相应的 LINK 或 STYLE 元素。对于 XML，可能是链接处理指令。对于被其他样式表包含的样式表，此属性的值为 null。 |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | 对于支持样式表包含概念的样式表语言，此属性表示包含的样式表（如果存在）。如果样式表是顶层样式表，或该语言不支持包含，则此属性的值为 null。 |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | 建议的标题。 |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | 这指定了此样式表的样式表语言。样式表语言以内容类型指定（例如 "text/css"）。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
